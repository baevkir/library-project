# library-project
Maven repository project

Add next to pom.xml to add this repository into ypur project:

{code}
 <repositories>
        <repository>
            <id>library-project-mvn-repo</id>
            <url>https://raw.github.com/baevkir/library-project/mvn-repo/</url>
            <snapshots>
                <enabled>true</enabled>
                <updatePolicy>always</updatePolicy>
            </snapshots>
        </repository>
</repositories>
{code}
