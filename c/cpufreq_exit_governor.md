# Function: <code>cpufreq_exit_governor</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8171237f)
Location: drivers/cpufreq/cpufreq.c:2046
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
**Symbols:**

```
ffffffff81712170-ffffffff817121c9: cpufreq_exit_governor.part.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81744bb4)
Location: drivers/cpufreq/cpufreq.c:2018
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
**Symbols:**

```
ffffffff817436b0-ffffffff81743703: cpufreq_exit_governor.part.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817638bc)
Location: drivers/cpufreq/cpufreq.c:2021
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
**Symbols:**

```
ffffffff81761d30-ffffffff81761d83: cpufreq_exit_governor.part.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817d98b1)
Location: drivers/cpufreq/cpufreq.c:2054
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
**Symbols:**

```
ffffffff817d7d10-ffffffff817d7d66: cpufreq_exit_governor.part.23 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_exit_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81820660)
Location: drivers/cpufreq/cpufreq.c:2053
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
**Symbols:**

```
ffffffff81820660-ffffffff818206c9: cpufreq_exit_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_exit_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8184c510)
Location: drivers/cpufreq/cpufreq.c:2054
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
**Symbols:**

```
ffffffff8184c510-ffffffff8184c579: cpufreq_exit_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_exit_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8188f580)
Location: drivers/cpufreq/cpufreq.c:2204
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
**Symbols:**

```
ffffffff8188f580-ffffffff8188f5e9: cpufreq_exit_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_exit_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818c15e0)
Location: drivers/cpufreq/cpufreq.c:2218
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
**Symbols:**

```
ffffffff818c15e0-ffffffff818c1649: cpufreq_exit_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_exit_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff819931c0)
Location: drivers/cpufreq/cpufreq.c:2255
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff819931c0-ffffffff8199322c: cpufreq_exit_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_exit_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81996370)
Location: drivers/cpufreq/cpufreq.c:2331
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff81996370-ffffffff819963dc: cpufreq_exit_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_exit_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8197b140)
Location: drivers/cpufreq/cpufreq.c:2337
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff8197b140-ffffffff8197b1ac: cpufreq_exit_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cpufreq_exit_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81a24640)
Location: drivers/cpufreq/cpufreq.c:2339
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff81a24610-ffffffff81a24688: cpufreq_exit_governor (STB_LOCAL)
ffffffff81d2be52-ffffffff81d2be67: cpufreq_exit_governor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cpufreq_exit_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81b8dd70)
Location: drivers/cpufreq/cpufreq.c:2379
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:__cpufreq_offline
```
**Symbols:**

```
ffffffff81b8dd40-ffffffff81b8ddc6: cpufreq_exit_governor (STB_LOCAL)
ffffffff81ef80a2-ffffffff81ef80b7: cpufreq_exit_governor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cpufreq_exit_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d2d780)
Location: drivers/cpufreq/cpufreq.c:2376
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:__cpufreq_offline
```
**Symbols:**

```
ffffffff81d2d750-ffffffff81d2d7df: cpufreq_exit_governor (STB_LOCAL)
ffffffff820a8cb6-ffffffff820a8ccb: cpufreq_exit_governor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cpufreq_exit_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d96a00)
Location: drivers/cpufreq/cpufreq.c:2383
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:__cpufreq_offline
```
**Symbols:**

```
ffffffff81d969d0-ffffffff81d96a5f: cpufreq_exit_governor (STB_LOCAL)
ffffffff82129ecf-ffffffff82129ee4: cpufreq_exit_governor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cpufreq_exit_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81e4e660)
Location: drivers/cpufreq/cpufreq.c:2424
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:__cpufreq_offline
```
**Symbols:**

```
ffffffff81e4e630-ffffffff81e4e6bf: cpufreq_exit_governor (STB_LOCAL)
ffffffff8220bca9-ffffffff8220bcbe: cpufreq_exit_governor.cold (STB_LOCAL)
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
void cpufreq_exit_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffff800010b1dfe8)
Location: drivers/cpufreq/cpufreq.c:2218
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
**Symbols:**

```
ffff800010b1dfe8-ffff800010b1e070: cpufreq_exit_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_exit_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c0bf9c24)
Location: drivers/cpufreq/cpufreq.c:2218
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
**Symbols:**

```
c0bf9c24-c0bf9cbc: cpufreq_exit_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_exit_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c000000000c125b0)
Location: drivers/cpufreq/cpufreq.c:2218
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
**Symbols:**

```
c000000000c125b0-c000000000c1266c: cpufreq_exit_governor (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_exit_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81865d00)
Location: drivers/cpufreq/cpufreq.c:2218
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
**Symbols:**

```
ffffffff81865d00-ffffffff81865d69: cpufreq_exit_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_exit_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8182e9b0)
Location: drivers/cpufreq/cpufreq.c:2218
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
**Symbols:**

```
ffffffff8182e9b0-ffffffff8182ea19: cpufreq_exit_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_exit_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818b6a90)
Location: drivers/cpufreq/cpufreq.c:2218
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
**Symbols:**

```
ffffffff818b6a90-ffffffff818b6af9: cpufreq_exit_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_exit_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818d35f0)
Location: drivers/cpufreq/cpufreq.c:2218
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
**Symbols:**

```
ffffffff818d35f0-ffffffff818d3659: cpufreq_exit_governor (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
