```java
package pkg1.pkg7.acceso.a.datos;

/**
 *
 * @author ____________________
 */
public class ArteASCII {
    public static void main(String[] args) {

        String[] asciiArt = {

            " ▄▀▀▄    ▄▀▀▄  ▄▀▀█▄▄▄▄  ▄▀▀▀▀▄     ▄▀▄▄▄▄   ▄▀▀▀▀▄   ▄▀▀▄ ▄▀▄  ▄▀▀█▄▄▄▄ ",
            "█   █    ▐  █ ▐  ▄▀   ▐ █    █     █ █    ▌ █      █ █  █ ▀  █ ▐  ▄▀   ▐ ",
            "▐  █        █   █▄▄▄▄▄  ▐    █     ▐ █      █      █ ▐  █    █   █▄▄▄▄▄  ",
            "  █   ▄    █    █    ▌      █        █      ▀▄    ▄▀   █    █    █    ▌  ",
            "   ▀▄▀ ▀▄ ▄▀   ▄▀▄▄▄▄     ▄▀▄▄▄▄▄▄▀ ▄▀▄▄▄▄▀   ▀▀▀▀   ▄▀   ▄▀    ▄▀▄▄▄▄   ",
            "         ▀     █    ▐     █        █     ▐           █    █     █    ▐   ",
            "               ▐          ▐        ▐                 ▐    ▐     ▐        "
        };

        for (String line : asciiArt) {
            System.out.println(line);
        }
    }
}

```
