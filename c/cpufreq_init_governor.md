# Function: <code>cpufreq_init_governor</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_init_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817130d0)
Location: drivers/cpufreq/cpufreq.c:2002
Inline: True
```
**Symbols:**

```
ffffffff817130d0-ffffffff817131c3: cpufreq_init_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_init_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81744f30)
Location: drivers/cpufreq/cpufreq.c:1974
Inline: True
```
**Symbols:**

```
ffffffff81744f30-ffffffff81745014: cpufreq_init_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_init_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81763650)
Location: drivers/cpufreq/cpufreq.c:1977
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff81763650-ffffffff81763730: cpufreq_init_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_init_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817d9610)
Location: drivers/cpufreq/cpufreq.c:2010
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff817d9610-ffffffff817d9701: cpufreq_init_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cpufreq_init_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:2009
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff81822190-ffffffff81822273: cpufreq_init_governor (STB_LOCAL)
ffffffff8182326f-ffffffff8182328b: cpufreq_init_governor.cold.48 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cpufreq_init_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8184e060)
Location: drivers/cpufreq/cpufreq.c:2010
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff8184e010-ffffffff8184e0f3: cpufreq_init_governor (STB_LOCAL)
ffffffff8184f12f-ffffffff8184f14b: cpufreq_init_governor.cold.50 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cpufreq_init_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81891218)
Location: drivers/cpufreq/cpufreq.c:2160
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff818911c0-ffffffff818912a4: cpufreq_init_governor (STB_LOCAL)
ffffffff8189259e-ffffffff818925ba: cpufreq_init_governor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cpufreq_init_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818c3408)
Location: drivers/cpufreq/cpufreq.c:2174
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff818c33b0-ffffffff818c3494: cpufreq_init_governor (STB_LOCAL)
ffffffff818c463d-ffffffff818c4659: cpufreq_init_governor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81995a2c)
Location: drivers/cpufreq/cpufreq.c:2211
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff819957c0-ffffffff8199587f: cpufreq_init_governor.part.0 (STB_LOCAL)
ffffffff8199688f-ffffffff819968ab: cpufreq_init_governor.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff819988e9)
Location: drivers/cpufreq/cpufreq.c:2285
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff819985d0-ffffffff819986aa: cpufreq_init_governor.part.0 (STB_LOCAL)
ffffffff81c298a4-ffffffff81c298c0: cpufreq_init_governor.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8197d409)
Location: drivers/cpufreq/cpufreq.c:2291
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff8197cf40-ffffffff8197d01a: cpufreq_init_governor.part.0 (STB_LOCAL)
ffffffff81c1bc0a-ffffffff81c1bc26: cpufreq_init_governor.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cpufreq_init_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81a25fad)
Location: drivers/cpufreq/cpufreq.c:2293
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff81a25f80-ffffffff81a26062: cpufreq_init_governor (STB_LOCAL)
ffffffff81d2bff4-ffffffff81d2c025: cpufreq_init_governor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int cpufreq_init_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:2333
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff81b8f940-ffffffff81b8fa34: cpufreq_init_governor (STB_LOCAL)
ffffffff81ef8260-ffffffff81ef8291: cpufreq_init_governor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int cpufreq_init_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:2330
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff81d2f9f0-ffffffff81d2fb0c: cpufreq_init_governor (STB_LOCAL)
ffffffff820a8d89-ffffffff820a8d9e: cpufreq_init_governor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int cpufreq_init_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:2337
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff81d98cd0-ffffffff81d98dec: cpufreq_init_governor (STB_LOCAL)
ffffffff82129fa2-ffffffff82129fb7: cpufreq_init_governor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int cpufreq_init_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:2378
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff81e50950-ffffffff81e50a6c: cpufreq_init_governor (STB_LOCAL)
ffffffff8220bd7c-ffffffff8220bd91: cpufreq_init_governor.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_init_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffff800010b20d40)
Location: drivers/cpufreq/cpufreq.c:2174
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffff800010b20d40-ffff800010b20e34: cpufreq_init_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_init_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c0bfb388)
Location: drivers/cpufreq/cpufreq.c:2174
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
c0bfb388-c0bfb490: cpufreq_init_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_init_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c000000000c14910)
Location: drivers/cpufreq/cpufreq.c:2174
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
c000000000c14910-c000000000c14a94: cpufreq_init_governor (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cpufreq_init_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81867b28)
Location: drivers/cpufreq/cpufreq.c:2174
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff81867ad0-ffffffff81867bb4: cpufreq_init_governor (STB_LOCAL)
ffffffff81868d5d-ffffffff81868d79: cpufreq_init_governor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cpufreq_init_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818307d8)
Location: drivers/cpufreq/cpufreq.c:2174
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff81830780-ffffffff81830864: cpufreq_init_governor (STB_LOCAL)
ffffffff81831a0d-ffffffff81831a29: cpufreq_init_governor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cpufreq_init_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818b88b8)
Location: drivers/cpufreq/cpufreq.c:2174
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff818b8860-ffffffff818b8944: cpufreq_init_governor (STB_LOCAL)
ffffffff818b9aed-ffffffff818b9b09: cpufreq_init_governor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cpufreq_init_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818d4b78)
Location: drivers/cpufreq/cpufreq.c:2174
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff818d4b20-ffffffff818d4c04: cpufreq_init_governor (STB_LOCAL)
ffffffff818d5dcd-ffffffff818d5de9: cpufreq_init_governor.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
