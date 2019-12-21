### build steps

ensure graalvm and native-image features are installed.

```
./gradlew assemble
native-image --no-server -cp build/libs/customer-svc-0.1-all.jar

```
