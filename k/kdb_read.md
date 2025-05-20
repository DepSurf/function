# Function: <code>kdb_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
char *kdb_read(char *buffer, size_t bufsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff81132920)
Location: kernel/debug/kdb/kdb_io.c:203
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
```
**Symbols:**

```
ffffffff81132920-ffffffff81133363: kdb_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
char *kdb_read(char *buffer, size_t bufsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff8113ad20)
Location: kernel/debug/kdb/kdb_io.c:203
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
```
**Symbols:**

```
ffffffff8113ad20-ffffffff8113b78f: kdb_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
char *kdb_read(char *buffer, size_t bufsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff81144ad0)
Location: kernel/debug/kdb/kdb_io.c:204
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
```
**Symbols:**

```
ffffffff81144ad0-ffffffff8114553f: kdb_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
char *kdb_read(char *buffer, size_t bufsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff81146710)
Location: kernel/debug/kdb/kdb_io.c:204
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
```
**Symbols:**

```
ffffffff81146710-ffffffff811472b9: kdb_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
char *kdb_read(char *buffer, size_t bufsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff81153040)
Location: kernel/debug/kdb/kdb_io.c:204
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
```
**Symbols:**

```
ffffffff81153040-ffffffff81153b40: kdb_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
char *kdb_read(char *buffer, size_t bufsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (0)
Location: kernel/debug/kdb/kdb_io.c:204
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
```
**Symbols:**

```
ffffffff81161b90-ffffffff81162654: kdb_read (STB_LOCAL)
ffffffff81162760-ffffffff81162790: kdb_read.cold.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
char *kdb_read(char *buffer, size_t bufsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (0)
Location: kernel/debug/kdb/kdb_io.c:204
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
```
**Symbols:**

```
ffffffff8116e9c0-ffffffff8116f53a: kdb_read (STB_LOCAL)
ffffffff8116f640-ffffffff8116f670: kdb_read.cold.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
char *kdb_read(char *buffer, size_t bufsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (0)
Location: kernel/debug/kdb/kdb_io.c:204
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
```
**Symbols:**

```
ffffffff8117b7c0-ffffffff8117c2dd: kdb_read (STB_LOCAL)
ffffffff8117c3dd-ffffffff8117c42b: kdb_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
char *kdb_read(char *buffer, size_t bufsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (0)
Location: kernel/debug/kdb/kdb_io.c:204
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
```
**Symbols:**

```
ffffffff81187650-ffffffff8118817f: kdb_read (STB_LOCAL)
ffffffff8118827d-ffffffff811882ad: kdb_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
char *kdb_read(char *buffer, size_t bufsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (0)
Location: kernel/debug/kdb/kdb_io.c:196
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
**Symbols:**

```
ffffffff8119bda0-ffffffff8119c6ab: kdb_read (STB_LOCAL)
ffffffff8119c7d3-ffffffff8119c803: kdb_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
char *kdb_read(char *buffer, size_t bufsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (0)
Location: kernel/debug/kdb/kdb_io.c:196
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
```
**Symbols:**

```
ffffffff81198ec0-ffffffff811997cb: kdb_read (STB_LOCAL)
ffffffff81be4de4-ffffffff81be4e14: kdb_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
char *kdb_read(char *buffer, size_t bufsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (0)
Location: kernel/debug/kdb/kdb_io.c:196
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
```
**Symbols:**

```
ffffffff81199c80-ffffffff8119a5d1: kdb_read (STB_LOCAL)
ffffffff81bd6c58-ffffffff81bd6c88: kdb_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
char *kdb_read(char *buffer, size_t bufsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (0)
Location: kernel/debug/kdb/kdb_io.c:196
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
```
**Symbols:**

```
ffffffff811c3af0-ffffffff811c4441: kdb_read (STB_LOCAL)
ffffffff81cb3c8e-ffffffff81cb3cbe: kdb_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
char *kdb_read(char *buffer, size_t bufsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (0)
Location: kernel/debug/kdb/kdb_io.c:195
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
```
**Symbols:**

```
ffffffff811f7330-ffffffff811f7c6a: kdb_read (STB_LOCAL)
ffffffff81e64b38-ffffffff81e64b68: kdb_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *kdb_read(char *buffer, size_t bufsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff8123e690)
Location: kernel/debug/kdb/kdb_io.c:195
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
```
**Symbols:**

```
ffffffff8123e690-ffffffff8123effa: kdb_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *kdb_read(char *buffer, size_t bufsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff81255780)
Location: kernel/debug/kdb/kdb_io.c:208
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
```
**Symbols:**

```
ffffffff81255780-ffffffff8125606b: kdb_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *kdb_read(char *buffer, size_t bufsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff8126f600)
Location: kernel/debug/kdb/kdb_io.c:208
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
```
**Symbols:**

```
ffffffff8126f600-ffffffff8126feeb: kdb_read (STB_LOCAL)
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
char *kdb_read(char *buffer, size_t bufsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffff8000101fd750)
Location: kernel/debug/kdb/kdb_io.c:204
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
```
**Symbols:**

```
ffff8000101fd750-ffff8000101fe24c: kdb_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
char *kdb_read(char *buffer, size_t bufsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (c043d838)
Location: kernel/debug/kdb/kdb_io.c:204
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
```
**Symbols:**

```
c043d838-c043e3a0: kdb_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
char *kdb_read(char *buffer, size_t bufsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (c0000000002760e0)
Location: kernel/debug/kdb/kdb_io.c:204
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
```
**Symbols:**

```
c0000000002760e0-c000000000277038: kdb_read (STB_LOCAL)
```
</details>
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
char *kdb_read(char *buffer, size_t bufsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (0)
Location: kernel/debug/kdb/kdb_io.c:204
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
```
**Symbols:**

```
ffffffff8117fc70-ffffffff8118079f: kdb_read (STB_LOCAL)
ffffffff8118089d-ffffffff811808cd: kdb_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
char *kdb_read(char *buffer, size_t bufsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (0)
Location: kernel/debug/kdb/kdb_io.c:204
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
```
**Symbols:**

```
ffffffff81172db0-ffffffff811738df: kdb_read (STB_LOCAL)
ffffffff811739dd-ffffffff81173a0d: kdb_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
char *kdb_read(char *buffer, size_t bufsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (0)
Location: kernel/debug/kdb/kdb_io.c:204
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
```
**Symbols:**

```
ffffffff8117da40-ffffffff8117e56f: kdb_read (STB_LOCAL)
ffffffff8117e66d-ffffffff8117e69d: kdb_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
char *kdb_read(char *buffer, size_t bufsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (0)
Location: kernel/debug/kdb/kdb_io.c:204
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
```
**Symbols:**

```
ffffffff8118b360-ffffffff8118be8f: kdb_read (STB_LOCAL)
ffffffff8118bf8d-ffffffff8118bfbd: kdb_read.cold (STB_LOCAL)
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
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
