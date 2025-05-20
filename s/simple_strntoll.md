# Function: <code>simple_strntoll</code>

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
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff815fc913)
Location: lib/vsprintf.c:126
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:simple_strtoll
  - lib/vsprintf.c:simple_strtoll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8166a5ae)
Location: lib/vsprintf.c:127
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:simple_strtoll
  - lib/vsprintf.c:simple_strtoll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81784478)
Location: lib/vsprintf.c:131
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:simple_strtoll
  - lib/vsprintf.c:simple_strtoll
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff82041448)
Location: lib/vsprintf.c:132
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:simple_strtoll
  - lib/vsprintf.c:simple_strtoll
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff820bf958)
Location: lib/vsprintf.c:132
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:simple_strtoll
  - lib/vsprintf.c:simple_strtoll
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long long int simple_strntoll(const char *cp, char **endp, unsigned int base, size_t max_chars);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff82199330)
Location: lib/vsprintf.c:135
Inline: False
Direct callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:simple_strtoll
```
**Symbols:**

```
ffffffff82199330-ffffffff8219936a: simple_strntoll (STB_LOCAL)
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
</ul>
