# Function: <code>early_platform_driver_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int early_platform_driver_register(struct early_platform_driver *epdrv, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81fac91d)
Location: drivers/base/platform.c:1155
Inline: False
```
**Symbols:**

```
ffffffff81fac91d-ffffffff81facaa9: early_platform_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int early_platform_driver_register(struct early_platform_driver *epdrv, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81fd9326)
Location: drivers/base/platform.c:1175
Inline: False
```
**Symbols:**

```
ffffffff81fd9326-ffffffff81fd94b6: early_platform_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int early_platform_driver_register(struct early_platform_driver *epdrv, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff82016fdf)
Location: drivers/base/platform.c:1189
Inline: False
```
**Symbols:**

```
ffffffff82016fdf-ffffffff8201716f: early_platform_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int early_platform_driver_register(struct early_platform_driver *epdrv, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff820f8d49)
Location: drivers/base/platform.c:1196
Inline: False
```
**Symbols:**

```
ffffffff820f8d49-ffffffff820f8eda: early_platform_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int early_platform_driver_register(struct early_platform_driver *epdrv, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff827023fd)
Location: drivers/base/platform.c:1198
Inline: False
```
**Symbols:**

```
ffffffff827023fd-ffffffff8270258e: early_platform_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int early_platform_driver_register(struct early_platform_driver *epdrv, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8272c136)
Location: drivers/base/platform.c:1214
Inline: False
```
**Symbols:**

```
ffffffff8272c136-ffffffff8272c2c7: early_platform_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int early_platform_driver_register(struct early_platform_driver *epdrv, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff828e4a92)
Location: drivers/base/platform.c:1193
Inline: False
```
**Symbols:**

```
ffffffff828e4a92-ffffffff828e4c23: early_platform_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int early_platform_driver_register(struct early_platform_driver *epdrv, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff828ff1e0)
Location: drivers/base/platform.c:1233
Inline: False
```
**Symbols:**

```
ffffffff828ff1e0-ffffffff828ff36e: early_platform_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int early_platform_driver_register(struct early_platform_driver *epdrv, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff82908383)
Location: drivers/base/platform.c:1317
Inline: False
```
**Symbols:**

```
ffffffff82908383-ffffffff82908511: early_platform_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int early_platform_driver_register(struct early_platform_driver *epdrv, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffff800011496cb4)
Location: drivers/base/platform.c:1317
Inline: False
Direct callers:
  - drivers/clocksource/sh_cmt.c:early_platform_driver_setup_func
  - drivers/clocksource/sh_tmu.c:early_platform_driver_setup_func
```
**Symbols:**

```
ffff800011496cb4-ffff800011496e64: early_platform_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int early_platform_driver_register(struct early_platform_driver *epdrv, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (c1597afc)
Location: drivers/base/platform.c:1317
Inline: False
Direct callers:
  - drivers/clocksource/sh_cmt.c:early_platform_driver_setup_func
  - drivers/clocksource/sh_mtu2.c:early_platform_driver_setup_func
  - drivers/clocksource/sh_tmu.c:early_platform_driver_setup_func
```
**Symbols:**

```
c1597afc-c1597cac: early_platform_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int early_platform_driver_register(struct early_platform_driver *epdrv, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (c0000000013aa258)
Location: drivers/base/platform.c:1317
Inline: False
```
**Symbols:**

```
c0000000013aa258-c0000000013aa488: early_platform_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int early_platform_driver_register(struct early_platform_driver *epdrv, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffe0000308f8)
Location: drivers/base/platform.c:1317
Inline: False
```
**Symbols:**

```
ffffffe0000308f8-ffffffe000030a44: early_platform_driver_register (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int early_platform_driver_register(struct early_platform_driver *epdrv, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff828efb54)
Location: drivers/base/platform.c:1317
Inline: False
```
**Symbols:**

```
ffffffff828efb54-ffffffff828efce2: early_platform_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int early_platform_driver_register(struct early_platform_driver *epdrv, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff828e6fe0)
Location: drivers/base/platform.c:1317
Inline: False
```
**Symbols:**

```
ffffffff828e6fe0-ffffffff828e716e: early_platform_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int early_platform_driver_register(struct early_platform_driver *epdrv, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff829036a6)
Location: drivers/base/platform.c:1317
Inline: False
```
**Symbols:**

```
ffffffff829036a6-ffffffff82903834: early_platform_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int early_platform_driver_register(struct early_platform_driver *epdrv, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff829093e5)
Location: drivers/base/platform.c:1317
Inline: False
```
**Symbols:**

```
ffffffff829093e5-ffffffff82909573: early_platform_driver_register (STB_GLOBAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
