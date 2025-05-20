# Function: <code>cpuidle_find_governor</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct cpuidle_governor *cpuidle_find_governor(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff818cfbb0)
Location: drivers/cpuidle/governor.c:31
Inline: False
Direct callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
```
**Symbols:**

```
ffffffff818cfbb0-ffffffff818cfc0c: cpuidle_find_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct cpuidle_governor *cpuidle_find_governor(const char *str);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff819a22c1)
Location: drivers/cpuidle/governor.c:31
Inline: True
Inline callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
```
**Symbols:**

```
ffffffff819a21f0-ffffffff819a224c: cpuidle_find_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct cpuidle_governor *cpuidle_find_governor(const char *str);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff819a5281)
Location: drivers/cpuidle/governor.c:31
Inline: True
Inline callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
```
**Symbols:**

```
ffffffff819a51b0-ffffffff819a520c: cpuidle_find_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct cpuidle_governor *cpuidle_find_governor(const char *str);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff81989ef1)
Location: drivers/cpuidle/governor.c:31
Inline: True
Inline callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
```
**Symbols:**

```
ffffffff81989e20-ffffffff81989e7c: cpuidle_find_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct cpuidle_governor *cpuidle_find_governor(const char *str);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff81a34851)
Location: drivers/cpuidle/governor.c:31
Inline: True
Inline callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
```
**Symbols:**

```
ffffffff81a34780-ffffffff81a347dc: cpuidle_find_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct cpuidle_governor *cpuidle_find_governor(const char *str);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff81ba10b1)
Location: drivers/cpuidle/governor.c:31
Inline: True
Inline callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
```
**Symbols:**

```
ffffffff81ba0f20-ffffffff81ba0f8e: cpuidle_find_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct cpuidle_governor *cpuidle_find_governor(const char *str);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff81d42da1)
Location: drivers/cpuidle/governor.c:31
Inline: True
Inline callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
```
**Symbols:**

```
ffffffff81d42bf0-ffffffff81d42c5e: cpuidle_find_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct cpuidle_governor *cpuidle_find_governor(const char *str);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff81dacfc1)
Location: drivers/cpuidle/governor.c:31
Inline: True
Inline callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
```
**Symbols:**

```
ffffffff81dace10-ffffffff81dace7e: cpuidle_find_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct cpuidle_governor *cpuidle_find_governor(const char *str);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff81e65061)
Location: drivers/cpuidle/governor.c:31
Inline: True
Inline callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
```
**Symbols:**

```
ffffffff81e64eb0-ffffffff81e64f1e: cpuidle_find_governor (STB_GLOBAL)
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
struct cpuidle_governor *cpuidle_find_governor(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governor.c (ffff800010b27e48)
Location: drivers/cpuidle/governor.c:31
Inline: False
Direct callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
```
**Symbols:**

```
ffff800010b27e48-ffff800010b27ed0: cpuidle_find_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct cpuidle_governor *cpuidle_find_governor(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governor.c (c0c02b0c)
Location: drivers/cpuidle/governor.c:31
Inline: False
Direct callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
```
**Symbols:**

```
c0c02b0c-c0c02b7c: cpuidle_find_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct cpuidle_governor *cpuidle_find_governor(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governor.c (c000000000c1f290)
Location: drivers/cpuidle/governor.c:31
Inline: False
Direct callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
```
**Symbols:**

```
c000000000c1f290-c000000000c1f35c: cpuidle_find_governor (STB_GLOBAL)
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
struct cpuidle_governor *cpuidle_find_governor(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff81873650)
Location: drivers/cpuidle/governor.c:31
Inline: False
Direct callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
```
**Symbols:**

```
ffffffff81873650-ffffffff818736ac: cpuidle_find_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct cpuidle_governor *cpuidle_find_governor(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff8183d440)
Location: drivers/cpuidle/governor.c:31
Inline: False
Direct callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
```
**Symbols:**

```
ffffffff8183d440-ffffffff8183d49c: cpuidle_find_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct cpuidle_governor *cpuidle_find_governor(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff818c5060)
Location: drivers/cpuidle/governor.c:31
Inline: False
Direct callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
```
**Symbols:**

```
ffffffff818c5060-ffffffff818c50bc: cpuidle_find_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct cpuidle_governor *cpuidle_find_governor(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governor.c (ffffffff818e14c0)
Location: drivers/cpuidle/governor.c:31
Inline: False
Direct callers:
  - drivers/cpuidle/governor.c:cpuidle_register_governor
```
**Symbols:**

```
ffffffff818e14c0-ffffffff818e151c: cpuidle_find_governor (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
