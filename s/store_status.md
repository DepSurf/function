# Function: <code>store_status</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t store_status(struct kobject *a, struct attribute *b, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8176c620)
Location: drivers/cpufreq/intel_pstate.c:1013
Inline: False
```
**Symbols:**

```
ffffffff8176c620-ffffffff8176c77c: store_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t store_status(struct kobject *a, struct attribute *b, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff817e2340)
Location: drivers/cpufreq/intel_pstate.c:828
Inline: False
```
**Symbols:**

```
ffffffff817e2340-ffffffff817e249c: store_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
int store_status(int *status, int start, int value, int nr);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81271ab5)
Location: mm/migrate.c:1461
Inline: True
Inline callers:
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:kernel_move_pages
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8182b120)
Location: drivers/cpufreq/intel_pstate.c:859
Inline: False
```
**Symbols:**

```
ffffffff8182b120-ffffffff8182b284: store_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
int store_status(int *status, int start, int value, int nr);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812860d5)
Location: mm/migrate.c:1494
Inline: True
Inline callers:
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:kernel_move_pages
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81857090)
Location: drivers/cpufreq/intel_pstate.c:921
Inline: False
```
**Symbols:**

```
ffffffff81857090-ffffffff818571f4: store_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline ⚠️</summary>

```c
int store_status(int *status, int start, int value, int nr);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a061a)
Location: mm/migrate.c:1489
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8189a7f0)
Location: drivers/cpufreq/intel_pstate.c:958
Inline: False
```
**Symbols:**

```
ffffffff8189a7f0-ffffffff8189a958: store_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
int store_status(int *status, int start, int value, int nr);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812b19c8)
Location: mm/migrate.c:1490
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818cc9a0)
Location: drivers/cpufreq/intel_pstate.c:957
Inline: False
```
**Symbols:**

```
ffffffff818cc9a0-ffffffff818ccb08: store_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int store_status(int *status, int start, int value, int nr);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812e72cf)
Location: mm/migrate.c:1507
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8199f2c0)
Location: drivers/cpufreq/intel_pstate.c:964
Inline: False
```
**Symbols:**

```
ffffffff8199f2c0-ffffffff8199f47a: store_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
int store_status(int *status, int start, int value, int nr);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812f2813)
Location: mm/migrate.c:1624
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff819a1a90)
Location: drivers/cpufreq/intel_pstate.c:1066
Inline: False
```
**Symbols:**

```
ffffffff819a1a90-ffffffff819a1c45: store_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
int store_status(int *status, int start, int value, int nr);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812f8bb3)
Location: mm/migrate.c:1606
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81986a70)
Location: drivers/cpufreq/intel_pstate.c:1068
Inline: False
```
**Symbols:**

```
ffffffff81986a70-ffffffff81986c24: store_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline ⚠️</summary>

```c
int store_status(int *status, int start, int value, int nr);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8134328e)
Location: mm/migrate.c:1650
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81a30ec0)
Location: drivers/cpufreq/intel_pstate.c:1168
Inline: False
```
**Symbols:**

```
ffffffff81a30ec0-ffffffff81a31074: store_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline ⚠️</summary>

```c
int store_status(int *status, int start, int value, int nr);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff813b5a14)
Location: mm/migrate.c:1581
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81b9cfa0)
Location: drivers/cpufreq/intel_pstate.c:1201
Inline: False
```
**Symbols:**

```
ffffffff81b9cfa0-ffffffff81b9d179: store_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
int store_status(int *status, int start, int value, int nr);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81435b14)
Location: mm/migrate.c:1688
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81d3ec40)
Location: drivers/cpufreq/intel_pstate.c:1176
Inline: False
```
**Symbols:**

```
ffffffff81d3ec40-ffffffff81d3ee19: store_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
int store_status(int *status, int start, int value, int nr);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8146b805)
Location: mm/migrate.c:2019
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81da97c0)
Location: drivers/cpufreq/intel_pstate.c:1196
Inline: False
```
**Symbols:**

```
ffffffff81da97c0-ffffffff81da9999: store_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int store_status(int *status, int start, int value, int nr);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8149a7dd)
Location: mm/migrate.c:2043
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:move_pages_and_store_status
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81e61660)
Location: drivers/cpufreq/intel_pstate.c:1220
Inline: False
```
**Symbols:**

```
ffffffff81e61660-ffffffff81e61839: store_status (STB_LOCAL)
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
int store_status(int *status, int start, int value, int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffff80001034e860)
Location: mm/migrate.c:1490
Inline: False
Direct callers:
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
```
**Symbols:**

```
ffff80001034e860-ffff80001034e9f0: store_status (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int store_status(int *status, int start, int value, int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c000000000431de0)
Location: mm/migrate.c:1490
Inline: False
Direct callers:
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
```
**Symbols:**

```
c000000000431de0-c000000000431eb8: store_status (STB_LOCAL)
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
<summary>In <code>aws</code>: Collision, Selective Inline ⚠️</summary>

```c
int store_status(int *status, int start, int value, int nr);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a9fa8)
Location: mm/migrate.c:1490
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818705a0)
Location: drivers/cpufreq/intel_pstate.c:957
Inline: False
```
**Symbols:**

```
ffffffff818705a0-ffffffff81870708: store_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline ⚠️</summary>

```c
int store_status(int *status, int start, int value, int nr);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8129b908)
Location: mm/migrate.c:1490
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81839b20)
Location: drivers/cpufreq/intel_pstate.c:957
Inline: False
```
**Symbols:**

```
ffffffff81839b20-ffffffff81839c88: store_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
int store_status(int *status, int start, int value, int nr);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a7db8)
Location: mm/migrate.c:1490
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818c1e50)
Location: drivers/cpufreq/intel_pstate.c:957
Inline: False
```
**Symbols:**

```
ffffffff818c1e50-ffffffff818c1fb8: store_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
int store_status(int *status, int start, int value, int nr);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812b80b8)
Location: mm/migrate.c:1490
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818de160)
Location: drivers/cpufreq/intel_pstate.c:957
Inline: False
```
**Symbols:**

```
ffffffff818de160-ffffffff818de2c8: store_status (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int *status</code>
</li>
<li>
<b>Param added. </b>
<code>int start</code>
</li>
<li>
<b>Param added. </b>
<code>int value</code>
</li>
<li>
<b>Param added. </b>
<code>int nr</code>
</li>
<li>
<b>Param removed. </b>
<code>struct kobject *a</code>
</li>
<li>
<b>Param removed. </b>
<code>struct attribute *b</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *buf</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t count</code>
</li>
<li>
<b>Return type changed. </b>
<code>ssize_t</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
