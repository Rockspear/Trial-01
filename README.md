# Trial-01
Basic chrome web 
import java.util.Base64;

public class Base64Decoder {
    public static void main(String[] args) {
        String encodedText = "U3ViamVjdDogTmV3IFBsYW5ldCBEZWNvZGluZXkgQWRkIFJlc291cmNlcyBhbmQgTGlua3MgPHNlbmRlciBvciBsaW5rcw==";
        byte[] decodedBytes = Base64.getDecoder().decode(encodedText);
        String decodedText = new String(decodedBytes);
        System.out.println(decodedText);
    }
}

