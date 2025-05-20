# Function: <code>__next_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct aa_ns *__next_ns(struct aa_ns *root, struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81374b00)
Location: security/apparmor/apparmorfs.c:792
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__first_profile
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
```
**Symbols:**

```
ffffffff81374b00-ffffffff81374c2d: __next_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct aa_ns *__next_ns(struct aa_ns *root, struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813aaef0)
Location: security/apparmor/apparmorfs.c:1286
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__first_profile
```
**Symbols:**

```
ffffffff813aaef0-ffffffff813ab027: __next_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct aa_ns *__next_ns(struct aa_ns *root, struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813c1a70)
Location: security/apparmor/apparmorfs.c:1392
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__first_profile
```
**Symbols:**

```
ffffffff813c1a70-ffffffff813c1bab: __next_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct aa_ns *__next_ns(struct aa_ns *root, struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813d8f70)
Location: security/apparmor/apparmorfs.c:1913
Inline: True
Direct callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:next_profile
  - security/apparmor/apparmorfs.c:next_profile
```
**Symbols:**

```
ffffffff813d8f70-ffffffff813d9002: __next_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct aa_ns *__next_ns(struct aa_ns *root, struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813fefe0)
Location: security/apparmor/apparmorfs.c:1977
Inline: True
Direct callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:next_profile
  - security/apparmor/apparmorfs.c:next_profile
```
**Symbols:**

```
ffffffff813fefe0-ffffffff813ff072: __next_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct aa_ns *__next_ns(struct aa_ns *root, struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8142ff70)
Location: security/apparmor/apparmorfs.c:1974
Inline: True
Direct callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:next_profile
  - security/apparmor/apparmorfs.c:next_profile
```
**Symbols:**

```
ffffffff8142ff70-ffffffff81430004: __next_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct aa_ns *__next_ns(struct aa_ns *root, struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8144cac0)
Location: security/apparmor/apparmorfs.c:1972
Inline: True
Direct callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:next_profile
  - security/apparmor/apparmorfs.c:next_profile
```
**Symbols:**

```
ffffffff8144cac0-ffffffff8144cb54: __next_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct aa_ns *__next_ns(struct aa_ns *root, struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8147a930)
Location: security/apparmor/apparmorfs.c:1977
Inline: True
Direct callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:next_profile
```
**Symbols:**

```
ffffffff8147a930-ffffffff8147a9c5: __next_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct aa_ns *__next_ns(struct aa_ns *root, struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81494630)
Location: security/apparmor/apparmorfs.c:1945
Inline: True
Direct callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:next_profile
```
**Symbols:**

```
ffffffff81494630-ffffffff814946c5: __next_ns (STB_LOCAL)
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
In security/apparmor/apparmorfs.c (ffffffff814ebf4e)
Location: security/apparmor/apparmorfs.c:2064
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:p_start
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
In security/apparmor/apparmorfs.c (ffffffff8150932e)
Location: security/apparmor/apparmorfs.c:2061
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:p_start
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
In security/apparmor/apparmorfs.c (ffffffff8150fd6a)
Location: security/apparmor/apparmorfs.c:2062
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:p_start
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
In security/apparmor/apparmorfs.c (ffffffff8156d9fa)
Location: security/apparmor/apparmorfs.c:2062
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:p_start
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
In security/apparmor/apparmorfs.c (ffffffff8160a0b6)
Location: security/apparmor/apparmorfs.c:2082
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:p_start
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
In security/apparmor/apparmorfs.c (ffffffff816bc136)
Location: security/apparmor/apparmorfs.c:2271
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:p_start
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
In security/apparmor/apparmorfs.c (ffffffff816f4c16)
Location: security/apparmor/apparmorfs.c:2319
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:p_start
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
In security/apparmor/apparmorfs.c (ffffffff81731966)
Location: security/apparmor/apparmorfs.c:2317
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_next
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:p_start
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct aa_ns *__next_ns(struct aa_ns *root, struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffff800010589d70)
Location: security/apparmor/apparmorfs.c:1945
Inline: True
Direct callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:next_profile
```
**Symbols:**

```
ffff800010589d70-ffff800010589e38: __next_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct aa_ns *__next_ns(struct aa_ns *root, struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (c073aed4)
Location: security/apparmor/apparmorfs.c:1945
Inline: True
Direct callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:next_profile
```
**Symbols:**

```
c073aed4-c073af74: __next_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct aa_ns *__next_ns(struct aa_ns *root, struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (c0000000006fb150)
Location: security/apparmor/apparmorfs.c:1945
Inline: True
Direct callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:next_profile
```
**Symbols:**

```
c0000000006fb150-c0000000006fb264: __next_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct aa_ns *__next_ns(struct aa_ns *root, struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffe0003d9308)
Location: security/apparmor/apparmorfs.c:1945
Inline: True
Direct callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:next_profile
```
**Symbols:**

```
ffffffe0003d9308-ffffffe0003d93b4: __next_ns (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct aa_ns *__next_ns(struct aa_ns *root, struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8148cc10)
Location: security/apparmor/apparmorfs.c:1945
Inline: True
Direct callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:next_profile
```
**Symbols:**

```
ffffffff8148cc10-ffffffff8148cca5: __next_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct aa_ns *__next_ns(struct aa_ns *root, struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8147d630)
Location: security/apparmor/apparmorfs.c:1945
Inline: True
Direct callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:next_profile
```
**Symbols:**

```
ffffffff8147d630-ffffffff8147d6c5: __next_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct aa_ns *__next_ns(struct aa_ns *root, struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81488cb0)
Location: security/apparmor/apparmorfs.c:1945
Inline: True
Direct callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:next_profile
```
**Symbols:**

```
ffffffff81488cb0-ffffffff81488d45: __next_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct aa_ns *__next_ns(struct aa_ns *root, struct aa_ns *ns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff814a07f0)
Location: security/apparmor/apparmorfs.c:1945
Inline: True
Direct callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:next_profile
```
**Symbols:**

```
ffffffff814a07f0-ffffffff814a0885: __next_ns (STB_LOCAL)
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
