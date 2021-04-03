```
# vugufmt -d .
diff -u root.vugu.orig root.vugu
--- root.vugu.orig      2021-04-03 10:32:45.840000000 -0500
+++ root.vugu   2021-04-03 10:32:45.840000000 -0500
@@ -1,7 +1,7 @@
 <div class="root">
-    <ul>
-      <components:MyLine FileName="example.txt" :LineNumber="rand.Int63n(100)" ></components:MyLine>
-    </ul>
+       <ul>
+               <components:myline filename="example.txt" :linenumber="rand.Int63n(100)" ></components:myline>
+       </ul>
 </div>

 <script type="application/x-go">
 #
```

```
# vugufmt -d components/my-line.vugu
#
```

