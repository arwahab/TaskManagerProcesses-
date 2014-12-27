package taskmgrproc;

import java.util.*;
import java.io.*;

public class TaskMgrProc {

    public static void main(String[] args) throws IOException {
        String line;
        Process p = Runtime.getRuntime().exec("tasklist.exe");
        BufferedReader input = new BufferedReader(new InputStreamReader(p.getInputStream()));
        while ((line = input.readLine()) != null) {
            System.out.println(line); //<-- Parse data here.
        }
        input.close();

    }

}
