# EncryptedPreferences
source code from http://www.drdobbs.com/security/encrypted-preferences-in-java/184416587?pgno=1

# Usage
1. Add our repository into your .pom
    <repositories>
        <repository>
            <id>SimpleFSM-mvn-repo</id>
            <url>https://raw.github.com/bvn13/SimpleFSM/mvn-repo/</url>
            <snapshots>
                <enabled>true</enabled>
                <updatePolicy>always</updatePolicy>
            </snapshots>
        </repository>
    </repositories>
2. Add dependency
    <dependencies>
        <!-- EncryptedPreferences -->
        <dependency>
            <groupId>ru.bvn13</groupId>
            <artifactId>EncryptedPreferences</artifactId>
            <version>1.0</version>
        </dependency>
    </dependencies>
3. Use it!
