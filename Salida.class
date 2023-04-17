package org.example;

import java.io.FileOutputStream;
import java.io.IOException;

public class Salida {
    public Salida() {
    }

    static void escribir() {
        byte CR = 13;
        byte LF = 10;

        try {
            FileOutputStream fos = new FileOutputStream("fich1.bin");
            fos.write(97);
            fos.write(101);
            fos.write(105);
            fos.write(CR);
            fos.write(LF);
            fos.close();
        } catch (IOException var3) {
            System.out.println(var3);
        }

    }
}
