//Uruchamienie w cmd.exe nie w powerShell - Windows
mvn clean install
java -cp target/classes;target/dependency/* com.kumuluz.ee.EeApplication

//Linux
java -cp target/classes:target/dependency/* com.kumuluz.ee.EeApplication