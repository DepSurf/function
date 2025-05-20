# Function: <code>free_sched_groups</code>

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
In kernel/sched/core.c (ffffffff810a6716)
Location: kernel/sched/core.c:5932
Inline: True
Inline callers:
  - kernel/sched/core.c:free_sched_domain
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
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
In kernel/sched/core.c (ffffffff810b1c0e)
Location: kernel/sched/core.c:5893
Inline: True
Inline callers:
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:free_sched_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b7f8c)
Location: kernel/sched/core.c:5931
Inline: True
Inline callers:
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:destroy_sched_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810cc904)
Location: kernel/sched/topology.c:326
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:destroy_sched_domain
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
In kernel/sched/topology.c (ffffffff810d379f)
Location: kernel/sched/topology.c:343
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:destroy_sched_domain
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:destroy_sched_domain
```
**Symbols:**

```
ffffffff810d28f0-ffffffff810d294e: free_sched_groups.part.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (ffffffff810db461)
Location: kernel/sched/topology.c:335
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:destroy_sched_domain
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:destroy_sched_domain
```
**Symbols:**

```
ffffffff810da9e0-ffffffff810daa3e: free_sched_groups.part.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (ffffffff810e506a)
Location: kernel/sched/topology.c:529
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:destroy_sched_domain
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:destroy_sched_domain
```
**Symbols:**

```
ffffffff810e4530-ffffffff810e458e: free_sched_groups.part.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (ffffffff810ec013)
Location: kernel/sched/topology.c:558
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:destroy_sched_domain
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:destroy_sched_domain
```
**Symbols:**

```
ffffffff810eb160-ffffffff810eb1bf: free_sched_groups.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (ffffffff810f7839)
Location: kernel/sched/topology.c:558
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:destroy_sched_domain
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:destroy_sched_domain
```
**Symbols:**

```
ffffffff810f6b00-ffffffff810f6b5f: free_sched_groups.part.0 (STB_LOCAL)
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
In kernel/sched/topology.c (ffffffff81100b95)
Location: kernel/sched/topology.c:556
Inline: True
Inline callers:
  - kernel/sched/topology.c:__sdt_free
  - kernel/sched/topology.c:__sdt_free
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:destroy_sched_domain
Direct callers:
  - kernel/sched/topology.c:destroy_sched_domain
```
**Symbols:**

```
ffffffff81100890-ffffffff811008ef: free_sched_groups.part.0 (STB_LOCAL)
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
In kernel/sched/topology.c (ffffffff810ff6e5)
Location: kernel/sched/topology.c:584
Inline: True
Inline callers:
  - kernel/sched/topology.c:__sdt_free
  - kernel/sched/topology.c:__sdt_free
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:destroy_sched_domain
Direct callers:
  - kernel/sched/topology.c:destroy_sched_domain
```
**Symbols:**

```
ffffffff810ff3e0-ffffffff810ff43f: free_sched_groups.part.0 (STB_LOCAL)
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
In kernel/sched/topology.c (ffffffff81101785)
Location: kernel/sched/topology.c:584
Inline: True
Inline callers:
  - kernel/sched/topology.c:__sdt_free
  - kernel/sched/topology.c:__sdt_free
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:destroy_sched_domain
Direct callers:
  - kernel/sched/topology.c:destroy_sched_domain
```
**Symbols:**

```
ffffffff811014b0-ffffffff8110150f: free_sched_groups.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (ffffffff8111d842)
Location: kernel/sched/topology.c:584
Inline: True
Inline callers:
  - kernel/sched/topology.c:__sdt_free
  - kernel/sched/topology.c:__sdt_free
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:destroy_sched_domain
Direct callers:
  - kernel/sched/topology.c:destroy_sched_domain
```
**Symbols:**

```
ffffffff8111d6d0-ffffffff8111d72f: free_sched_groups.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81141214)
Location: kernel/sched/topology.c:604
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__sdt_free
  - kernel/sched/build_utility.c:__sdt_free
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:destroy_sched_domain
Direct callers:
  - kernel/sched/build_utility.c:destroy_sched_domain
```
**Symbols:**

```
ffffffff8113e770-ffffffff8113e7d6: free_sched_groups.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8116c4f7)
Location: kernel/sched/topology.c:604
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__sdt_free
  - kernel/sched/build_utility.c:__sdt_free
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:destroy_sched_domain
Direct callers:
  - kernel/sched/build_utility.c:destroy_sched_domain
```
**Symbols:**

```
ffffffff81168cf0-ffffffff81168d56: free_sched_groups.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8117c947)
Location: kernel/sched/topology.c:606
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__sdt_free
  - kernel/sched/build_utility.c:__sdt_free
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:destroy_sched_domain
Direct callers:
  - kernel/sched/build_utility.c:destroy_sched_domain
```
**Symbols:**

```
ffffffff81179460-ffffffff811794c6: free_sched_groups.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118a677)
Location: kernel/sched/topology.c:608
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__sdt_free
  - kernel/sched/build_utility.c:__sdt_free
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:destroy_sched_domain
Direct callers:
  - kernel/sched/build_utility.c:destroy_sched_domain
```
**Symbols:**

```
ffffffff81186fa0-ffffffff81187006: free_sched_groups.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (ffff80001015bb88)
Location: kernel/sched/topology.c:558
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:destroy_sched_domain
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:destroy_sched_domain
```
**Symbols:**

```
ffff80001015ac90-ffff80001015ad58: free_sched_groups.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (c03a8654)
Location: kernel/sched/topology.c:558
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:destroy_sched_domain
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:destroy_sched_domain
```
**Symbols:**

```
c03a76f0-c03a77a4: free_sched_groups.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (c0000000001b0310)
Location: kernel/sched/topology.c:558
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:destroy_sched_domain
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:destroy_sched_domain
```
**Symbols:**

```
c0000000001aef10-c0000000001af000: free_sched_groups.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (ffffffe000100d8a)
Location: kernel/sched/topology.c:558
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:destroy_sched_domain
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:destroy_sched_domain
```
**Symbols:**

```
ffffffe0001003b6-ffffffe000100436: free_sched_groups.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (ffffffff810f0c39)
Location: kernel/sched/topology.c:558
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:destroy_sched_domain
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:destroy_sched_domain
```
**Symbols:**

```
ffffffff810eff00-ffffffff810eff5f: free_sched_groups.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (ffffffff810e0ca9)
Location: kernel/sched/topology.c:558
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:destroy_sched_domain
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:destroy_sched_domain
```
**Symbols:**

```
ffffffff810dff70-ffffffff810dffcf: free_sched_groups.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (ffffffff810edd69)
Location: kernel/sched/topology.c:558
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:destroy_sched_domain
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:destroy_sched_domain
```
**Symbols:**

```
ffffffff810ed030-ffffffff810ed08f: free_sched_groups.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/topology.c (ffffffff810f8da9)
Location: kernel/sched/topology.c:558
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:destroy_sched_domain
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:destroy_sched_domain
```
**Symbols:**

```
ffffffff810f8070-ffffffff810f80cf: free_sched_groups.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
