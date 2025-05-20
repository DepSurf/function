# Function: <code>cros_ec_query_all</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int cros_ec_query_all(struct cros_ec_device *ec_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff816e36b0)
Location: drivers/platform/chrome/cros_ec_proto.c:237
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer
```
**Symbols:**

```
ffffffff816e36b0-ffffffff816e3a3c: cros_ec_query_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cros_ec_query_all(struct cros_ec_device *ec_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff817479b0)
Location: drivers/platform/chrome/cros_ec_proto.c:237
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer
```
**Symbols:**

```
ffffffff817479b0-ffffffff81747d0a: cros_ec_query_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cros_ec_query_all(struct cros_ec_device *ec_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff8177b2c0)
Location: drivers/platform/chrome/cros_ec_proto.c:270
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer
```
**Symbols:**

```
ffffffff8177b2c0-ffffffff8177b686: cros_ec_query_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cros_ec_query_all(struct cros_ec_device *ec_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81799cd0)
Location: drivers/platform/chrome/cros_ec_proto.c:320
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer
```
**Symbols:**

```
ffffffff81799cd0-ffffffff8179a0ee: cros_ec_query_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cros_ec_query_all(struct cros_ec_device *ec_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81810070)
Location: drivers/platform/chrome/cros_ec_proto.c:322
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer
```
**Symbols:**

```
ffffffff81810070-ffffffff8181048e: cros_ec_query_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cros_ec_query_all(struct cros_ec_device *ec_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81859f10)
Location: drivers/platform/chrome/cros_ec_proto.c:324
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer
```
**Symbols:**

```
ffffffff81859f10-ffffffff8185a32e: cros_ec_query_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cros_ec_query_all(struct cros_ec_device *ec_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff818791b0)
Location: drivers/platform/chrome/cros_ec_proto.c:324
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer
```
**Symbols:**

```
ffffffff818791b0-ffffffff818795ce: cros_ec_query_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int cros_ec_query_all(struct cros_ec_device *ec_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: drivers/platform/chrome/cros_ec_proto.c:328
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer
```
**Symbols:**

```
ffffffff818bec65-ffffffff818becb2: cros_ec_query_all.cold (STB_LOCAL)
ffffffff818be370-ffffffff818be74f: cros_ec_query_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int cros_ec_query_all(struct cros_ec_device *ec_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: drivers/platform/chrome/cros_ec_proto.c:329
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer
```
**Symbols:**

```
ffffffff818f17b5-ffffffff818f1802: cros_ec_query_all.cold (STB_LOCAL)
ffffffff818f0ec0-ffffffff818f129f: cros_ec_query_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cros_ec_query_all(struct cros_ec_device *ec_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff819c64b0)
Location: drivers/platform/chrome/cros_ec_proto.c:359
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer
```
**Symbols:**

```
ffffffff819c64b0-ffffffff819c6817: cros_ec_query_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cros_ec_query_all(struct cros_ec_device *ec_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff819c63a0)
Location: drivers/platform/chrome/cros_ec_proto.c:402
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer_status
```
**Symbols:**

```
ffffffff819c63a0-ffffffff819c6756: cros_ec_query_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int cros_ec_query_all(struct cros_ec_device *ec_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: drivers/platform/chrome/cros_ec_proto.c:402
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer_status
```
**Symbols:**

```
ffffffff81c1faaf-ffffffff81c1fafc: cros_ec_query_all.cold (STB_LOCAL)
ffffffff819ab250-ffffffff819ab6a8: cros_ec_query_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int cros_ec_query_all(struct cros_ec_device *ec_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: drivers/platform/chrome/cros_ec_proto.c:411
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer_status
```
**Symbols:**

```
ffffffff81d31340-ffffffff81d3138d: cros_ec_query_all.cold (STB_LOCAL)
ffffffff81a58d30-ffffffff81a5917c: cros_ec_query_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int cros_ec_query_all(struct cros_ec_device *ec_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: drivers/platform/chrome/cros_ec_proto.c:413
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer
```
**Symbols:**

```
ffffffff81efd7a2-ffffffff81efd7ef: cros_ec_query_all.cold (STB_LOCAL)
ffffffff81bc8b30-ffffffff81bc8f92: cros_ec_query_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cros_ec_query_all(struct cros_ec_device *ec_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81d71ef0)
Location: drivers/platform/chrome/cros_ec_proto.c:496
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer
```
**Symbols:**

```
ffffffff81d71ef0-ffffffff81d721cf: cros_ec_query_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cros_ec_query_all(struct cros_ec_device *ec_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81ddfbd0)
Location: drivers/platform/chrome/cros_ec_proto.c:496
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer
```
**Symbols:**

```
ffffffff81ddfbd0-ffffffff81ddfeb3: cros_ec_query_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cros_ec_query_all(struct cros_ec_device *ec_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81e95b80)
Location: drivers/platform/chrome/cros_ec_proto.c:496
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer
```
**Symbols:**

```
ffffffff81e95b80-ffffffff81e95e92: cros_ec_query_all (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int cros_ec_query_all(struct cros_ec_device *ec_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffff800010b78f00)
Location: drivers/platform/chrome/cros_ec_proto.c:329
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer
```
**Symbols:**

```
ffff800010b78f00-ffff800010b79314: cros_ec_query_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cros_ec_query_all(struct cros_ec_device *ec_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (c0c5e830)
Location: drivers/platform/chrome/cros_ec_proto.c:329
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer
```
**Symbols:**

```
c0c5e830-c0c5ecb0: cros_ec_query_all (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int cros_ec_query_all(struct cros_ec_device *ec_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: drivers/platform/chrome/cros_ec_proto.c:329
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer
```
**Symbols:**

```
ffffffff81892ae5-ffffffff81892b32: cros_ec_query_all.cold (STB_LOCAL)
ffffffff818921f0-ffffffff818925cf: cros_ec_query_all (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int cros_ec_query_all(struct cros_ec_device *ec_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: drivers/platform/chrome/cros_ec_proto.c:329
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer
```
**Symbols:**

```
ffffffff818e65e5-ffffffff818e6632: cros_ec_query_all.cold (STB_LOCAL)
ffffffff818e5cf0-ffffffff818e60cf: cros_ec_query_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int cros_ec_query_all(struct cros_ec_device *ec_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: drivers/platform/chrome/cros_ec_proto.c:329
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer
```
**Symbols:**

```
ffffffff81903265-ffffffff819032b2: cros_ec_query_all.cold (STB_LOCAL)
ffffffff81902970-ffffffff81902d4f: cros_ec_query_all (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
