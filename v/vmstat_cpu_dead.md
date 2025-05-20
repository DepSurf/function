# Function: <code>vmstat_cpu_dead</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811ad879)
Location: mm/vmstat.c:1491
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpuup_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811c6ac8)
Location: mm/vmstat.c:1797
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpuup_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vmstat_cpu_dead(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811d6c30)
Location: mm/vmstat.c:1744
Inline: False
```
**Symbols:**

```
ffffffff811d6c30-ffffffff811d6c7a: vmstat_cpu_dead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vmstat_cpu_dead(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811dfa90)
Location: mm/vmstat.c:1747
Inline: False
```
**Symbols:**

```
ffffffff811dfa90-ffffffff811dfada: vmstat_cpu_dead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vmstat_cpu_dead(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811f58a0)
Location: mm/vmstat.c:1971
Inline: False
```
**Symbols:**

```
ffffffff811f58a0-ffffffff811f58ea: vmstat_cpu_dead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int vmstat_cpu_dead(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81216b20)
Location: mm/vmstat.c:1928
Inline: False
```
**Symbols:**

```
ffffffff81216b20-ffffffff81216b6a: vmstat_cpu_dead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int vmstat_cpu_dead(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81229a30)
Location: mm/vmstat.c:1931
Inline: False
```
**Symbols:**

```
ffffffff81229a30-ffffffff81229a7a: vmstat_cpu_dead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int vmstat_cpu_dead(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812396d0)
Location: mm/vmstat.c:1927
Inline: False
```
**Symbols:**

```
ffffffff812396d0-ffffffff8123971a: vmstat_cpu_dead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vmstat_cpu_dead(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812479d0)
Location: mm/vmstat.c:1946
Inline: False
```
**Symbols:**

```
ffffffff812479d0-ffffffff81247a1a: vmstat_cpu_dead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vmstat_cpu_dead(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81275bc0)
Location: mm/vmstat.c:1955
Inline: False
```
**Symbols:**

```
ffffffff81275bc0-ffffffff81275c07: vmstat_cpu_dead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vmstat_cpu_dead(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812804a0)
Location: mm/vmstat.c:1998
Inline: False
```
**Symbols:**

```
ffffffff812804a0-ffffffff812804e7: vmstat_cpu_dead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vmstat_cpu_dead(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812855a0)
Location: mm/vmstat.c:2044
Inline: False
```
**Symbols:**

```
ffffffff812855a0-ffffffff812855e7: vmstat_cpu_dead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vmstat_cpu_dead(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812c3f40)
Location: mm/vmstat.c:2041
Inline: False
```
**Symbols:**

```
ffffffff812c3f40-ffffffff812c3fbc: vmstat_cpu_dead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vmstat_cpu_dead(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81321760)
Location: mm/vmstat.c:2075
Inline: False
```
**Symbols:**

```
ffffffff81321760-ffffffff813217f4: vmstat_cpu_dead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vmstat_cpu_dead(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81395770)
Location: mm/vmstat.c:2069
Inline: False
```
**Symbols:**

```
ffffffff81395770-ffffffff813957ff: vmstat_cpu_dead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vmstat_cpu_dead(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813c8390)
Location: mm/vmstat.c:2093
Inline: False
```
**Symbols:**

```
ffffffff813c8390-ffffffff813c841f: vmstat_cpu_dead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vmstat_cpu_dead(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813f2d80)
Location: mm/vmstat.c:2097
Inline: False
```
**Symbols:**

```
ffffffff813f2d80-ffffffff813f2e0f: vmstat_cpu_dead (STB_LOCAL)
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
int vmstat_cpu_dead(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffff8000102dbea8)
Location: mm/vmstat.c:1946
Inline: False
```
**Symbols:**

```
ffff8000102dbea8-ffff8000102dbf50: vmstat_cpu_dead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vmstat_cpu_dead(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c0501ef0)
Location: mm/vmstat.c:1946
Inline: False
```
**Symbols:**

```
c0501ef0-c0501f24: vmstat_cpu_dead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vmstat_cpu_dead(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c00000000039ba40)
Location: mm/vmstat.c:1946
Inline: False
```
**Symbols:**

```
c00000000039ba40-c00000000039bb1c: vmstat_cpu_dead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vmstat_cpu_dead(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffe0001f4fe2)
Location: mm/vmstat.c:1946
Inline: False
```
**Symbols:**

```
ffffffe0001f4fe2-ffffffe0001f5016: vmstat_cpu_dead (STB_LOCAL)
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
int vmstat_cpu_dead(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81240020)
Location: mm/vmstat.c:1946
Inline: False
```
**Symbols:**

```
ffffffff81240020-ffffffff8124006a: vmstat_cpu_dead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vmstat_cpu_dead(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81233020)
Location: mm/vmstat.c:1946
Inline: False
```
**Symbols:**

```
ffffffff81233020-ffffffff8123306a: vmstat_cpu_dead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vmstat_cpu_dead(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8123ddc0)
Location: mm/vmstat.c:1946
Inline: False
```
**Symbols:**

```
ffffffff8123ddc0-ffffffff8123de0a: vmstat_cpu_dead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vmstat_cpu_dead(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8124d4f0)
Location: mm/vmstat.c:1946
Inline: False
```
**Symbols:**

```
ffffffff8124d4f0-ffffffff8124d53a: vmstat_cpu_dead (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
