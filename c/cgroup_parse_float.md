# Function: <code>cgroup_parse_float</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cgroup_parse_float(const char *input, unsigned int dec_shift, s64 *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115b000)
Location: kernel/cgroup/cgroup.c:6320
Inline: False
```
**Symbols:**

```
ffffffff8115b000-ffffffff8115b134: cgroup_parse_float (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cgroup_parse_float(const char *input, unsigned int dec_shift, s64 *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81166cb0)
Location: kernel/cgroup/cgroup.c:6335
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff81166cb0-ffffffff81166de4: cgroup_parse_float (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cgroup_parse_float(const char *input, unsigned int dec_shift, s64 *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811783c0)
Location: kernel/cgroup/cgroup.c:6395
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff811783c0-ffffffff811784dd: cgroup_parse_float (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cgroup_parse_float(const char *input, unsigned int dec_shift, s64 *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81175100)
Location: kernel/cgroup/cgroup.c:6387
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff81175100-ffffffff8117521d: cgroup_parse_float (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cgroup_parse_float(const char *input, unsigned int dec_shift, s64 *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81175c40)
Location: kernel/cgroup/cgroup.c:6365
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff81175c40-ffffffff81175d75: cgroup_parse_float (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cgroup_parse_float(const char *input, unsigned int dec_shift, s64 *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8119d230)
Location: kernel/cgroup/cgroup.c:6611
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff8119d230-ffffffff8119d365: cgroup_parse_float (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cgroup_parse_float(const char *input, unsigned int dec_shift, s64 *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811cd570)
Location: kernel/cgroup/cgroup.c:6645
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff811cd570-ffffffff811cd6bb: cgroup_parse_float (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cgroup_parse_float(const char *input, unsigned int dec_shift, s64 *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81210bf0)
Location: kernel/cgroup/cgroup.c:6912
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff81210bf0-ffffffff81210d3b: cgroup_parse_float (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cgroup_parse_float(const char *input, unsigned int dec_shift, s64 *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff812265f0)
Location: kernel/cgroup/cgroup.c:6893
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff812265f0-ffffffff8122672d: cgroup_parse_float (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cgroup_parse_float(const char *input, unsigned int dec_shift, s64 *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8123e280)
Location: kernel/cgroup/cgroup.c:6934
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff8123e280-ffffffff8123e3bd: cgroup_parse_float (STB_GLOBAL)
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
int cgroup_parse_float(const char *input, unsigned int dec_shift, s64 *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d8ae8)
Location: kernel/cgroup/cgroup.c:6335
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffff8000101d8ae8-ffff8000101d8c40: cgroup_parse_float (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cgroup_parse_float(const char *input, unsigned int dec_shift, s64 *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c041b74c)
Location: kernel/cgroup/cgroup.c:6335
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
c041b74c-c041b97c: cgroup_parse_float (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cgroup_parse_float(const char *input, unsigned int dec_shift, s64 *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c000000000245e20)
Location: kernel/cgroup/cgroup.c:6335
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
c000000000245e20-c000000000245fd8: cgroup_parse_float (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cgroup_parse_float(const char *input, unsigned int dec_shift, s64 *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe000151aba)
Location: kernel/cgroup/cgroup.c:6335
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffe000151aba-ffffffe000151bb4: cgroup_parse_float (STB_GLOBAL)
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
int cgroup_parse_float(const char *input, unsigned int dec_shift, s64 *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115f2d0)
Location: kernel/cgroup/cgroup.c:6335
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff8115f2d0-ffffffff8115f404: cgroup_parse_float (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cgroup_parse_float(const char *input, unsigned int dec_shift, s64 *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81152560)
Location: kernel/cgroup/cgroup.c:6335
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff81152560-ffffffff81152694: cgroup_parse_float (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cgroup_parse_float(const char *input, unsigned int dec_shift, s64 *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115d0a0)
Location: kernel/cgroup/cgroup.c:6335
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff8115d0a0-ffffffff8115d1d4: cgroup_parse_float (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cgroup_parse_float(const char *input, unsigned int dec_shift, s64 *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116a1f0)
Location: kernel/cgroup/cgroup.c:6335
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff8116a1f0-ffffffff8116a324: cgroup_parse_float (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
