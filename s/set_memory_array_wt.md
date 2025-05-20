# Function: <code>set_memory_array_wt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int set_memory_array_wt(long unsigned int *addr, int addrinarray);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106e980)
Location: arch/x86/mm/pageattr.c:1583
Inline: False
```
**Symbols:**

```
ffffffff8106e980-ffffffff8106e995: set_memory_array_wt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int set_memory_array_wt(long unsigned int *addr, int addrinarray);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106e740)
Location: arch/x86/mm/pageattr.c:1591
Inline: False
```
**Symbols:**

```
ffffffff8106e740-ffffffff8106e755: set_memory_array_wt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int set_memory_array_wt(long unsigned int *addr, int addrinarray);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810723f0)
Location: arch/x86/mm/pageattr.c:1591
Inline: False
```
**Symbols:**

```
ffffffff810723f0-ffffffff81072405: set_memory_array_wt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int set_memory_array_wt(long unsigned int *addr, int addrinarray);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810719f0)
Location: arch/x86/mm/pageattr.c:1637
Inline: False
```
**Symbols:**

```
ffffffff810719f0-ffffffff81071a05: set_memory_array_wt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int set_memory_array_wt(long unsigned int *addr, int addrinarray);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81077090)
Location: arch/x86/mm/pageattr.c:1637
Inline: False
```
**Symbols:**

```
ffffffff81077090-ffffffff810770a5: set_memory_array_wt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int set_memory_array_wt(long unsigned int *addr, int addrinarray);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81079af0)
Location: arch/x86/mm/pageattr.c:1667
Inline: False
```
**Symbols:**

```
ffffffff81079af0-ffffffff81079b05: set_memory_array_wt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int set_memory_array_wt(long unsigned int *addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81080300)
Location: arch/x86/mm/pageattr.c:1862
Inline: False
```
**Symbols:**

```
ffffffff81080300-ffffffff81080315: set_memory_array_wt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int set_memory_array_wt(long unsigned int *addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81083dc0)
Location: arch/x86/mm/pageattr.c:1873
Inline: False
```
**Symbols:**

```
ffffffff81083dc0-ffffffff81083dd5: set_memory_array_wt (STB_GLOBAL)
```
</details>
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int numpages</code>
</li>
<li>
<b>Param removed. </b>
<code>int addrinarray</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
</ul>
