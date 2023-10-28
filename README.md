dependencies {
    compileOnly('jakarta.platform:jakarta.jakartaee-web-api:10.0.0')

    //for access DB
    implementation 'org.mariadb.jdbc:mariadb-java-client:3.2.0'
    implementation 'org.eclipse.persistence:eclipselink:4.0.2'

    //for logging
    implementation 'org.slf4j:slf4j-api:2.0.9'
    implementation 'org.slf4j:slf4j-simple:2.0.9'

    //for REST API
    implementation('org.glassfish.jersey.containers:jersey-container-servlet:3.1.2')
    implementation('org.glassfish.jersey.media:jersey-media-json-jackson:3.1.2')
    implementation('org.glassfish.jersey.inject:jersey-cdi2-se:3.1.2')
    implementation('org.jboss.weld.se:weld-se-core:5.1.0.Final')
    //for convert type in rest
    implementation 'com.fasterxml.jackson.datatype:jackson-datatype-jsr310:2.15.2'
    implementation 'com.fasterxml.jackson.datatype:jackson-datatype-jdk8:2.15.2'
    implementation 'com.fasterxml.jackson.module:jackson-module-parameter-names:2.15.2'

    implementation 'jakarta.json:jakarta.json-api:2.1.2'

    testImplementation("org.junit.jupiter:junit-jupiter-api:${junitVersion}")
    testRuntimeOnly("org.junit.jupiter:junit-jupiter-engine:${junitVersion}")
}




<properties>
            <property name="jakarta.persistence.jdbc.driver" value="org.mariadb.jdbc.Driver"/>
            <property name="jakarta.persistence.jdbc.url" value="jdbc:mariadb://localhost:33078/cv?createDatabaseIfNotExist=true"/>
            <property name="jakarta.persistence.jdbc.user" value="root"/>
            <property name="jakarta.persistence.jdbc.password" value="sapassword"/>
            <property name="hibernate.show_sql" value="true"/>
            <property name="hibernate.format_sql" value="true"/>
            <property name="hibernate.hbm2ddl.auto" value="update"/>
            <property name="hibernate.dialect" value="org.hibernate.dialect.MariaDBDialect"/>
        </properties>








<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet"
      integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.8/dist/umd/popper.min.js"
        integrity="sha384-I7E8VVD/ismYTF4hNIPjVp/Zjvgyol6VFvRkX/vR+Vc4jQkC+hVqc2pM8ODewa9r"
        crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.min.js"
        integrity="sha384-BBtl+eGJRgqQAUMxJ7pMwbEyER4l1g+O15P+16Ep7Q9Q+zqX6gSbd85u4mG4QzX+"
        crossorigin="anonymous"></script>
