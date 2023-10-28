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
