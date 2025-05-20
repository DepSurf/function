# Function: <code>dump_header</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dump_header(struct oom_control *oc, struct task_struct *p, struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81208ad4)
Location: mm/oom_kill.c:386
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff81208ad4-ffffffff81208c99: dump_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void dump_header(struct oom_control *oc, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8122e7ac)
Location: mm/oom_kill.c:400
Inline: True
```
**Symbols:**

```
ffffffff8122e7ac-ffffffff8122e988: dump_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void dump_header(struct oom_control *oc, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81240cd7)
Location: mm/oom_kill.c:404
Inline: True
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff81240cd7-ffffffff81240ed4: dump_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dump_header(struct oom_control *oc, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811bdd9b)
Location: mm/oom_kill.c:407
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff811bdd9b-ffffffff811bdfb5: dump_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dump_header(struct oom_control *oc, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811d29fb)
Location: mm/oom_kill.c:427
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff811d29fb-ffffffff811d2c7d: dump_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dump_header(struct oom_control *oc, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811f38fb)
Location: mm/oom_kill.c:422
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff811f38fb-ffffffff811f3b73: dump_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dump_header(struct oom_control *oc, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff812058cb)
Location: mm/oom_kill.c:443
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff812058cb-ffffffff81205bd3: dump_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dump_header(struct oom_control *oc, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8121d000)
Location: mm/oom_kill.c:452
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff8121d000-ffffffff8121d1eb: dump_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dump_header(struct oom_control *oc, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8122a9dd)
Location: mm/oom_kill.c:452
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff8122a9dd-ffffffff8122abc8: dump_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dump_header(struct oom_control *oc, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8125779b)
Location: mm/oom_kill.c:453
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff8125779b-ffffffff81257986: dump_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dump_header(struct oom_control *oc, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81be6aa2)
Location: mm/oom_kill.c:455
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff81be6aa2-ffffffff81be6c98: dump_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dump_header(struct oom_control *oc, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81bd8838)
Location: mm/oom_kill.c:454
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff81bd8838-ffffffff81bd8a31: dump_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dump_header(struct oom_control *oc, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81cba0ec)
Location: mm/oom_kill.c:455
Inline: False
Direct callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff81cba0ec-ffffffff81cba310: dump_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dump_header(struct oom_control *oc, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81e6b835)
Location: mm/oom_kill.c:452
Inline: False
Direct callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff81e6b835-ffffffff81e6ba7b: dump_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dump_header(struct oom_control *oc, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff813640c0)
Location: mm/oom_kill.c:452
Inline: False
Direct callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff813640c0-ffffffff81364349: dump_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dump_header(struct oom_control *oc, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81396590)
Location: mm/oom_kill.c:452
Inline: False
Direct callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff81396590-ffffffff81396819: dump_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dump_header(struct oom_control *oc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff813c0670)
Location: mm/oom_kill.c:453
Inline: False
Direct callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff813c0670-ffffffff813c0853: dump_header (STB_LOCAL)
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
void dump_header(struct oom_control *oc, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffff8000102b8d78)
Location: mm/oom_kill.c:452
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffff8000102b8d78-ffff8000102b8f58: dump_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dump_header(struct oom_control *oc, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (c04e5554)
Location: mm/oom_kill.c:452
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
c04e5554-c04e574c: dump_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dump_header(struct oom_control *oc, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (c000000000370eb4)
Location: mm/oom_kill.c:452
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
c000000000370eb4-c000000000371128: dump_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dump_header(struct oom_control *oc, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffe0001dc9ac)
Location: mm/oom_kill.c:452
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffe0001dc9ac-ffffffe0001dcb90: dump_header (STB_LOCAL)
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
void dump_header(struct oom_control *oc, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8122302d)
Location: mm/oom_kill.c:452
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff8122302d-ffffffff81223218: dump_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dump_header(struct oom_control *oc, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff812161dd)
Location: mm/oom_kill.c:452
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff812161dd-ffffffff812163c8: dump_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dump_header(struct oom_control *oc, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81220dcd)
Location: mm/oom_kill.c:452
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff81220dcd-ffffffff81220fb8: dump_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dump_header(struct oom_control *oc, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8122ff6d)
Location: mm/oom_kill.c:452
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff8122ff6d-ffffffff8123016d: dump_header (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct mem_cgroup *memcg</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct task_struct *p</code>
</li>
</ul>
</details>
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
