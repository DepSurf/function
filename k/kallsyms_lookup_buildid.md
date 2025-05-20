# Function: <code>kallsyms_lookup_buildid</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const char *kallsyms_lookup_buildid(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset, char **modname, const unsigned char **modbuildid, char *namebuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8118ac70)
Location: kernel/kallsyms.c:307
Inline: False
Direct callers:
  - kernel/kallsyms.c:kallsyms_lookup
```
**Symbols:**

```
ffffffff8118ac70-ffffffff8118adc0: kallsyms_lookup_buildid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const char *kallsyms_lookup_buildid(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset, char **modname, const unsigned char **modbuildid, char *namebuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff811b9de0)
Location: kernel/kallsyms.c:331
Inline: False
Direct callers:
  - kernel/kallsyms.c:kallsyms_lookup
```
**Symbols:**

```
ffffffff811b9de0-ffffffff811b9f60: kallsyms_lookup_buildid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *kallsyms_lookup_buildid(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset, char **modname, const unsigned char **modbuildid, char *namebuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff811fb610)
Location: kernel/kallsyms.c:404
Inline: False
Direct callers:
  - kernel/kallsyms.c:kallsyms_lookup
```
**Symbols:**

```
ffffffff811fb610-ffffffff811fb762: kallsyms_lookup_buildid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *kallsyms_lookup_buildid(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset, char **modname, const unsigned char **modbuildid, char *namebuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81210d10)
Location: kernel/kallsyms.c:399
Inline: False
Direct callers:
  - kernel/kallsyms.c:kallsyms_lookup
```
**Symbols:**

```
ffffffff81210d10-ffffffff81210e62: kallsyms_lookup_buildid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char *kallsyms_lookup_buildid(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset, char **modname, const unsigned char **modbuildid, char *namebuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81228390)
Location: kernel/kallsyms.c:397
Inline: False
Direct callers:
  - kernel/kallsyms.c:kallsyms_lookup
```
**Symbols:**

```
ffffffff81228390-ffffffff812284e2: kallsyms_lookup_buildid (STB_LOCAL)
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
