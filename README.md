## For Maven Build Hadoop 3.1.1

```
mvn $ANT_OPTS usr/lib/libsnappy.so -Pdist -Pnative -Psrc -Pyarn-ui -Dtar -Dzookeeper.version=3.4.13 -Djetty.version=9.3.29.v20201019 -DskipTests -DskipTest -DskipITs install package ${EXTRA_GOALS} "$@"
```
