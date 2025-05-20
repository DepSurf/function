# Function: <code>next_profile</code>

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
In security/apparmor/apparmorfs.c (ffffffff81375077)
Location: security/apparmor/apparmorfs.c:892
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
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
In security/apparmor/apparmorfs.c (ffffffff813ab557)
Location: security/apparmor/apparmorfs.c:1386
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
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
In security/apparmor/apparmorfs.c (ffffffff813c2324)
Location: security/apparmor/apparmorfs.c:1492
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct aa_profile *next_profile(struct aa_ns *root, struct aa_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813d9010)
Location: security/apparmor/apparmorfs.c:2014
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
```
**Symbols:**

```
ffffffff813d9010-ffffffff813d90ce: next_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct aa_profile *next_profile(struct aa_ns *root, struct aa_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813ff080)
Location: security/apparmor/apparmorfs.c:2078
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
```
**Symbols:**

```
ffffffff813ff080-ffffffff813ff13e: next_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct aa_profile *next_profile(struct aa_ns *root, struct aa_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81430010)
Location: security/apparmor/apparmorfs.c:2075
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
```
**Symbols:**

```
ffffffff81430010-ffffffff814300cd: next_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct aa_profile *next_profile(struct aa_ns *root, struct aa_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8144cb60)
Location: security/apparmor/apparmorfs.c:2073
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
```
**Symbols:**

```
ffffffff8144cb60-ffffffff8144cc1d: next_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct aa_profile *next_profile(struct aa_ns *root, struct aa_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8147a9d0)
Location: security/apparmor/apparmorfs.c:2078
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
```
**Symbols:**

```
ffffffff8147a9d0-ffffffff8147aa71: next_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct aa_profile *next_profile(struct aa_ns *root, struct aa_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff814946d0)
Location: security/apparmor/apparmorfs.c:2046
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
```
**Symbols:**

```
ffffffff814946d0-ffffffff81494771: next_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff814ebefa)
Location: security/apparmor/apparmorfs.c:2165
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:p_start
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
In security/apparmor/apparmorfs.c (ffffffff815092da)
Location: security/apparmor/apparmorfs.c:2162
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:p_start
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
In security/apparmor/apparmorfs.c (ffffffff8150fd0a)
Location: security/apparmor/apparmorfs.c:2163
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:p_start
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
In security/apparmor/apparmorfs.c (ffffffff8156d99a)
Location: security/apparmor/apparmorfs.c:2163
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:p_start
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
In security/apparmor/apparmorfs.c (ffffffff8160a04a)
Location: security/apparmor/apparmorfs.c:2183
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:p_start
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
In security/apparmor/apparmorfs.c (ffffffff816bc0ca)
Location: security/apparmor/apparmorfs.c:2372
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:p_start
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
In security/apparmor/apparmorfs.c (ffffffff816f4baa)
Location: security/apparmor/apparmorfs.c:2420
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:p_start
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
In security/apparmor/apparmorfs.c (ffffffff817318fa)
Location: security/apparmor/apparmorfs.c:2418
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:p_start
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
struct aa_profile *next_profile(struct aa_ns *root, struct aa_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffff800010589e38)
Location: security/apparmor/apparmorfs.c:2046
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
```
**Symbols:**

```
ffff800010589e38-ffff800010589f28: next_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct aa_profile *next_profile(struct aa_ns *root, struct aa_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (c073af74)
Location: security/apparmor/apparmorfs.c:2046
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
```
**Symbols:**

```
c073af74-c073b05c: next_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct aa_profile *next_profile(struct aa_ns *root, struct aa_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (c0000000006fb270)
Location: security/apparmor/apparmorfs.c:2046
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
```
**Symbols:**

```
c0000000006fb270-c0000000006fb39c: next_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct aa_profile *next_profile(struct aa_ns *root, struct aa_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffe0003d93b4)
Location: security/apparmor/apparmorfs.c:2046
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
```
**Symbols:**

```
ffffffe0003d93b4-ffffffe0003d9458: next_profile (STB_LOCAL)
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
struct aa_profile *next_profile(struct aa_ns *root, struct aa_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8148ccb0)
Location: security/apparmor/apparmorfs.c:2046
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
```
**Symbols:**

```
ffffffff8148ccb0-ffffffff8148cd51: next_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct aa_profile *next_profile(struct aa_ns *root, struct aa_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8147d6d0)
Location: security/apparmor/apparmorfs.c:2046
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
```
**Symbols:**

```
ffffffff8147d6d0-ffffffff8147d771: next_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct aa_profile *next_profile(struct aa_ns *root, struct aa_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81488d50)
Location: security/apparmor/apparmorfs.c:2046
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
```
**Symbols:**

```
ffffffff81488d50-ffffffff81488df1: next_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct aa_profile *next_profile(struct aa_ns *root, struct aa_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff814a0890)
Location: security/apparmor/apparmorfs.c:2046
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
```
**Symbols:**

```
ffffffff814a0890-ffffffff814a0931: next_profile (STB_LOCAL)
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
