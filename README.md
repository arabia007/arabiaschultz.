# arabiaschultz.
$ username
    runs-on: ubuntu-latest

    steps:

    - uses: actions/checkout@v2

    - name: set up JDK 1.8

      uses: actions/setup-java@v1

      with:

        java-version: 1.8

    - name: Build with Gradle

      run: ./gradlew build


