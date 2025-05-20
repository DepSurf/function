# Function: <code>xbc_init</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xbc_init(char *buf, const char **emsg, int *epos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff82d0a51d)
Location: lib/bootconfig.c:764
Inline: False
```
**Symbols:**

```
ffffffff82d0a51d-ffffffff82d0a839: xbc_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xbc_init(char *buf, const char **emsg, int *epos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff82ff7b04)
Location: lib/bootconfig.c:774
Inline: False
```
**Symbols:**

```
ffffffff82ff7b04-ffffffff82ff7e2d: xbc_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xbc_init(char *buf, const char **emsg, int *epos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff83202614)
Location: lib/bootconfig.c:774
Inline: False
Direct callers:
  - init/main.c:setup_boot_config
```
**Symbols:**

```
ffffffff83202614-ffffffff83202aa4: xbc_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xbc_init(char *buf, const char **emsg, int *epos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff832e9dc3)
Location: lib/bootconfig.c:814
Inline: False
Direct callers:
  - init/main.c:setup_boot_config
```
**Symbols:**

```
ffffffff832e9dc3-ffffffff832ea27a: xbc_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xbc_init(const char *data, size_t size, const char **emsg, int *epos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff834a1af0)
Location: lib/bootconfig.c:933
Inline: False
Direct callers:
  - init/main.c:setup_boot_config
```
**Symbols:**

```
ffffffff834a1af0-ffffffff834a1c3f: xbc_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xbc_init(const char *data, size_t size, const char **emsg, int *epos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff83edb1f0)
Location: lib/bootconfig.c:933
Inline: False
Direct callers:
  - init/main.c:setup_boot_config
```
**Symbols:**

```
ffffffff83edb1f0-ffffffff83edb44b: xbc_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xbc_init(const char *data, size_t size, const char **emsg, int *epos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff83700d20)
Location: lib/bootconfig.c:933
Inline: False
Direct callers:
  - init/main.c:setup_boot_config
```
**Symbols:**

```
ffffffff83700d20-ffffffff83700f7b: xbc_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xbc_init(const char *data, size_t size, const char **emsg, int *epos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff83934560)
Location: lib/bootconfig.c:933
Inline: False
Direct callers:
  - init/main.c:setup_boot_config
```
**Symbols:**

```
ffffffff83934560-ffffffff839347bb: xbc_init (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char *data</code>
</li>
<li>
<b>Param added. </b>
<code>size_t size</code>
</li>
<li>
<b>Param removed. </b>
<code>char *buf</code>
</li>
<li>
<b>Param reordered. </b>
<code>buf, emsg, epos</code> ➡️ <code>data, size, emsg, epos</code>
</li>
</ul>
</details>
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
