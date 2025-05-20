# Function: <code>do_set_mempolicy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff811e0d70)
Location: mm/mempolicy.c:753
Inline: False
Direct callers:
  - mm/mempolicy.c:compat_SyS_set_mempolicy
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_default_policy
```
**Symbols:**

```
ffffffff811e0d70-ffffffff811e0e9a: do_set_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff811ff740)
Location: mm/mempolicy.c:785
Inline: False
Direct callers:
  - mm/mempolicy.c:numa_default_policy
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:compat_SyS_set_mempolicy
```
**Symbols:**

```
ffffffff811ff740-ffffffff811ff86a: do_set_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81210b90)
Location: mm/mempolicy.c:787
Inline: False
Direct callers:
  - mm/mempolicy.c:numa_default_policy
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:SYSC_set_mempolicy
```
**Symbols:**

```
ffffffff81210b90-ffffffff81210cd2: do_set_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8121c530)
Location: mm/mempolicy.c:721
Inline: False
Direct callers:
  - mm/mempolicy.c:numa_default_policy
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:SYSC_set_mempolicy
```
**Symbols:**

```
ffffffff8121c530-ffffffff8121c652: do_set_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812376e0)
Location: mm/mempolicy.c:763
Inline: False
Direct callers:
  - mm/mempolicy.c:numa_default_policy
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:SYSC_set_mempolicy
```
**Symbols:**

```
ffffffff812376e0-ffffffff81237802: do_set_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8125ab60)
Location: mm/mempolicy.c:738
Inline: False
Direct callers:
  - mm/mempolicy.c:numa_default_policy
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:kernel_set_mempolicy
```
**Symbols:**

```
ffffffff8125ab60-ffffffff8125ac8a: do_set_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8126f320)
Location: mm/mempolicy.c:764
Inline: False
Direct callers:
  - mm/mempolicy.c:numa_default_policy
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:kernel_set_mempolicy
```
**Symbols:**

```
ffffffff8126f320-ffffffff8126f44a: do_set_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8128a900)
Location: mm/mempolicy.c:791
Inline: False
Direct callers:
  - mm/mempolicy.c:numa_default_policy
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:kernel_set_mempolicy
```
**Symbols:**

```
ffffffff8128a900-ffffffff8128aa27: do_set_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8129a470)
Location: mm/mempolicy.c:792
Inline: False
Direct callers:
  - mm/mempolicy.c:numa_default_policy
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:kernel_set_mempolicy
```
**Symbols:**

```
ffffffff8129a470-ffffffff8129a597: do_set_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812cda00)
Location: mm/mempolicy.c:862
Inline: False
Direct callers:
  - mm/mempolicy.c:numa_default_policy
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:kernel_set_mempolicy
```
**Symbols:**

```
ffffffff812cda00-ffffffff812cdb3c: do_set_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812d8930)
Location: mm/mempolicy.c:862
Inline: False
Direct callers:
  - mm/mempolicy.c:numa_default_policy
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:kernel_set_mempolicy
```
**Symbols:**

```
ffffffff812d8930-ffffffff812d8a77: do_set_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812dffc0)
Location: mm/mempolicy.c:862
Inline: False
Direct callers:
  - mm/mempolicy.c:numa_default_policy
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:kernel_set_mempolicy
```
**Symbols:**

```
ffffffff812dffc0-ffffffff812e0153: do_set_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81327500)
Location: mm/mempolicy.c:843
Inline: False
Direct callers:
  - mm/mempolicy.c:numa_default_policy
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:kernel_set_mempolicy
```
**Symbols:**

```
ffffffff81327500-ffffffff8132765b: do_set_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff813965c0)
Location: mm/mempolicy.c:842
Inline: False
Direct callers:
  - mm/mempolicy.c:numa_default_policy
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:kernel_set_mempolicy
```
**Symbols:**

```
ffffffff813965c0-ffffffff81396728: do_set_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81415ee0)
Location: mm/mempolicy.c:854
Inline: False
Direct callers:
  - mm/mempolicy.c:numa_default_policy
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:kernel_set_mempolicy
```
**Symbols:**

```
ffffffff81415ee0-ffffffff81416047: do_set_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff814495e0)
Location: mm/mempolicy.c:859
Inline: False
Direct callers:
  - mm/mempolicy.c:numa_default_policy
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:kernel_set_mempolicy
```
**Symbols:**

```
ffffffff814495e0-ffffffff81449746: do_set_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81483030)
Location: mm/mempolicy.c:813
Inline: False
Direct callers:
  - mm/mempolicy.c:numa_default_policy
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:kernel_set_mempolicy
```
**Symbols:**

```
ffffffff81483030-ffffffff814831c9: do_set_mempolicy (STB_LOCAL)
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
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffff800010338ea0)
Location: mm/mempolicy.c:792
Inline: False
Direct callers:
  - mm/mempolicy.c:numa_default_policy
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:kernel_set_mempolicy
```
**Symbols:**

```
ffff800010338ea0-ffff800010339000: do_set_mempolicy (STB_LOCAL)
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
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (c000000000413760)
Location: mm/mempolicy.c:792
Inline: False
Direct callers:
  - mm/mempolicy.c:numa_default_policy
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:kernel_set_mempolicy
```
**Symbols:**

```
c000000000413760-c00000000041390c: do_set_mempolicy (STB_LOCAL)
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
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81292a50)
Location: mm/mempolicy.c:792
Inline: False
Direct callers:
  - mm/mempolicy.c:numa_default_policy
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:kernel_set_mempolicy
```
**Symbols:**

```
ffffffff81292a50-ffffffff81292b77: do_set_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81284660)
Location: mm/mempolicy.c:792
Inline: False
Direct callers:
  - mm/mempolicy.c:numa_default_policy
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:kernel_set_mempolicy
```
**Symbols:**

```
ffffffff81284660-ffffffff81284787: do_set_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81290860)
Location: mm/mempolicy.c:792
Inline: False
Direct callers:
  - mm/mempolicy.c:numa_default_policy
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:kernel_set_mempolicy
```
**Symbols:**

```
ffffffff81290860-ffffffff81290987: do_set_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812a0690)
Location: mm/mempolicy.c:792
Inline: False
Direct callers:
  - mm/mempolicy.c:numa_default_policy
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:kernel_set_mempolicy
```
**Symbols:**

```
ffffffff812a0690-ffffffff812a07b3: do_set_mempolicy (STB_LOCAL)
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
