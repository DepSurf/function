# Function: <code>default_pointer</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
char *default_pointer(char *buf, char *end, const void *ptr, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (0)
Location: lib/vsprintf.c:834
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:restricted_pointer
```
**Symbols:**

```
ffffffff81787320-ffffffff8178751e: default_pointer (STB_LOCAL)
ffffffff81ea637a-ffffffff81ea6397: default_pointer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
char *default_pointer(char *buf, char *end, const void *ptr, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (0)
Location: lib/vsprintf.c:835
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:restricted_pointer
```
**Symbols:**

```
ffffffff820444d0-ffffffff820447ab: default_pointer (STB_LOCAL)
ffffffff820b7bb1-ffffffff820b7c08: default_pointer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
char *default_pointer(char *buf, char *end, const void *ptr, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (0)
Location: lib/vsprintf.c:835
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:restricted_pointer
```
**Symbols:**

```
ffffffff820c2ae0-ffffffff820c2d83: default_pointer (STB_LOCAL)
ffffffff82139031-ffffffff82139079: default_pointer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
char *default_pointer(char *buf, char *end, const void *ptr, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (0)
Location: lib/vsprintf.c:837
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:restricted_pointer
```
**Symbols:**

```
ffffffff8219d460-ffffffff8219d703: default_pointer (STB_LOCAL)
ffffffff8221add6-ffffffff8221ae1e: default_pointer.cold (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
