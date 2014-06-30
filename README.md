AccessSysApp
============

java code to access system applications:


package accesssysapp;

public class AccessSysApp {

    public static void main(String[] args) {
        Runtime objr = Runtime.getRuntime();
        try{
            objr.exec("calc");
        }catch(Exception e){    
        }
    }
    
}
