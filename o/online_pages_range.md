# Function: <code>online_pages_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int online_pages_range(long unsigned int start_pfn, long unsigned int nr_pages, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff811ef0f0)
Location: mm/memory_hotplug.c:866
Inline: False
```
**Symbols:**

```
ffffffff811ef0f0-ffffffff811ef156: online_pages_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int online_pages_range(long unsigned int start_pfn, long unsigned int nr_pages, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8120e3a0)
Location: mm/memory_hotplug.c:943
Inline: False
```
**Symbols:**

```
ffffffff8120e3a0-ffffffff8120e405: online_pages_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int online_pages_range(long unsigned int start_pfn, long unsigned int nr_pages, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812203e0)
Location: mm/memory_hotplug.c:929
Inline: False
```
**Symbols:**

```
ffffffff812203e0-ffffffff8122044e: online_pages_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int online_pages_range(long unsigned int start_pfn, long unsigned int nr_pages, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8122c2f0)
Location: mm/memory_hotplug.c:682
Inline: False
```
**Symbols:**

```
ffffffff8122c2f0-ffffffff8122c37f: online_pages_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int online_pages_range(long unsigned int start_pfn, long unsigned int nr_pages, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81247ac0)
Location: mm/memory_hotplug.c:691
Inline: False
```
**Symbols:**

```
ffffffff81247ac0-ffffffff81247b55: online_pages_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int online_pages_range(long unsigned int start_pfn, long unsigned int nr_pages, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8126b530)
Location: mm/memory_hotplug.c:667
Inline: False
```
**Symbols:**

```
ffffffff8126b530-ffffffff8126b5c5: online_pages_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int online_pages_range(long unsigned int start_pfn, long unsigned int nr_pages, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8127fdc0)
Location: mm/memory_hotplug.c:668
Inline: False
```
**Symbols:**

```
ffffffff8127fdc0-ffffffff8127fe55: online_pages_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int online_pages_range(long unsigned int start_pfn, long unsigned int nr_pages, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8129bd40)
Location: mm/memory_hotplug.c:653
Inline: False
```
**Symbols:**

```
ffffffff8129bd40-ffffffff8129bd9f: online_pages_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int online_pages_range(long unsigned int start_pfn, long unsigned int nr_pages, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812aba80)
Location: mm/memory_hotplug.c:618
Inline: False
```
**Symbols:**

```
ffffffff812aba80-ffffffff812abb4c: online_pages_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int online_pages_range(long unsigned int start_pfn, long unsigned int nr_pages, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812e0390)
Location: mm/memory_hotplug.c:612
Inline: False
```
**Symbols:**

```
ffffffff812e0390-ffffffff812e044b: online_pages_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81c3aa4d)
Location: mm/memory_hotplug.c:611
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81c2d035)
Location: mm/memory_hotplug.c:653
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
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
In mm/memory_hotplug.c (ffffffff81d4b909)
Location: mm/memory_hotplug.c:596
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
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
In mm/memory_hotplug.c (ffffffff81f1b218)
Location: mm/memory_hotplug.c:603
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
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
In mm/memory_hotplug.c (ffffffff820c3178)
Location: mm/memory_hotplug.c:593
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
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
In mm/memory_hotplug.c (ffffffff82146f26)
Location: mm/memory_hotplug.c:576
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff822296a4)
Location: mm/memory_hotplug.c:644
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
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
int online_pages_range(long unsigned int start_pfn, long unsigned int nr_pages, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffff80001034da08)
Location: mm/memory_hotplug.c:618
Inline: False
```
**Symbols:**

```
ffff80001034da08-ffff80001034db38: online_pages_range (STB_LOCAL)
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
int online_pages_range(long unsigned int start_pfn, long unsigned int nr_pages, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (c00000000042d6b0)
Location: mm/memory_hotplug.c:618
Inline: False
```
**Symbols:**

```
c00000000042d6b0-c00000000042d824: online_pages_range (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int online_pages_range(long unsigned int start_pfn, long unsigned int nr_pages, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812a4060)
Location: mm/memory_hotplug.c:618
Inline: False
```
**Symbols:**

```
ffffffff812a4060-ffffffff812a412c: online_pages_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int online_pages_range(long unsigned int start_pfn, long unsigned int nr_pages, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81295b30)
Location: mm/memory_hotplug.c:618
Inline: False
```
**Symbols:**

```
ffffffff81295b30-ffffffff81295bfc: online_pages_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int online_pages_range(long unsigned int start_pfn, long unsigned int nr_pages, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812a1e70)
Location: mm/memory_hotplug.c:618
Inline: False
```
**Symbols:**

```
ffffffff812a1e70-ffffffff812a1f3c: online_pages_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int online_pages_range(long unsigned int start_pfn, long unsigned int nr_pages, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812b2030)
Location: mm/memory_hotplug.c:618
Inline: False
```
**Symbols:**

```
ffffffff812b2030-ffffffff812b20fc: online_pages_range (STB_LOCAL)
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
