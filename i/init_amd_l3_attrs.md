# Function: <code>init_amd_l3_attrs</code>

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
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103f62b)
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:526
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cache_get_priv_group
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
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103f42b)
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:526
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cache_get_priv_group
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
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103ee5e)
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:527
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cache_get_priv_group
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
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103ce1e)
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:528
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cache_get_priv_group
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103f99e)
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:529
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cache_get_priv_group
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81040fae)
Location: arch/x86/kernel/cpu/cacheinfo.c:531
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810425be)
Location: arch/x86/kernel/cpu/cacheinfo.c:532
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81044a2e)
Location: arch/x86/kernel/cpu/cacheinfo.c:533
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8104517e)
Location: arch/x86/kernel/cpu/cacheinfo.c:533
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void init_amd_l3_attrs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81048320)
Location: arch/x86/kernel/cpu/cacheinfo.c:533
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
```
**Symbols:**

```
ffffffff81048320-ffffffff810483cc: init_amd_l3_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void init_amd_l3_attrs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81047810)
Location: arch/x86/kernel/cpu/cacheinfo.c:533
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
```
**Symbols:**

```
ffffffff81047810-ffffffff810478bc: init_amd_l3_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void init_amd_l3_attrs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81049030)
Location: arch/x86/kernel/cpu/cacheinfo.c:533
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
```
**Symbols:**

```
ffffffff81049030-ffffffff810490dc: init_amd_l3_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void init_amd_l3_attrs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8104f9f0)
Location: arch/x86/kernel/cpu/cacheinfo.c:533
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
```
**Symbols:**

```
ffffffff8104f9f0-ffffffff8104fa9c: init_amd_l3_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void init_amd_l3_attrs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8105b1e0)
Location: arch/x86/kernel/cpu/cacheinfo.c:533
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
```
**Symbols:**

```
ffffffff8105b1e0-ffffffff8105b2a0: init_amd_l3_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void init_amd_l3_attrs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81068b70)
Location: arch/x86/kernel/cpu/cacheinfo.c:546
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
```
**Symbols:**

```
ffffffff81068b70-ffffffff81068c30: init_amd_l3_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void init_amd_l3_attrs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106a480)
Location: arch/x86/kernel/cpu/cacheinfo.c:548
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
```
**Symbols:**

```
ffffffff8106a480-ffffffff8106a540: init_amd_l3_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void init_amd_l3_attrs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81071950)
Location: arch/x86/kernel/cpu/cacheinfo.c:557
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
```
**Symbols:**

```
ffffffff81071950-ffffffff81071a10: init_amd_l3_attrs (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810452fe)
Location: arch/x86/kernel/cpu/cacheinfo.c:533
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8103480e)
Location: arch/x86/kernel/cpu/cacheinfo.c:533
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8104513e)
Location: arch/x86/kernel/cpu/cacheinfo.c:533
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8104653e)
Location: arch/x86/kernel/cpu/cacheinfo.c:533
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
