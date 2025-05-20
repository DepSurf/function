# Function: <code>bpf_check_classic</code>

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
In net/core/filter.c (ffffffff81731dc8)
Location: net/core/filter.c:755
Inline: True
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
In net/core/filter.c (ffffffff8179dd9e)
Location: net/core/filter.c:782
Inline: True
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
In net/core/filter.c (ffffffff817cc7fe)
Location: net/core/filter.c:784
Inline: True
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
In net/core/filter.c (ffffffff817ebc4f)
Location: net/core/filter.c:802
Inline: True
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
In net/core/filter.c (ffffffff81867a1f)
Location: net/core/filter.c:821
Inline: True
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
In net/core/filter.c (ffffffff818b7bbf)
Location: net/core/filter.c:1030
Inline: True
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
In net/core/filter.c (ffffffff818de43f)
Location: net/core/filter.c:1032
Inline: True
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
In net/core/filter.c (ffffffff8192c42e)
Location: net/core/filter.c:1032
Inline: True
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
In net/core/filter.c (ffffffff8195e72e)
Location: net/core/filter.c:1032
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_check_classic(const struct sock_filter *filter, unsigned int flen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a30cd0)
Location: net/core/filter.c:1021
Inline: False
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
ffffffff81a30cd0-ffffffff81a30e5d: bpf_check_classic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_check_classic(const struct sock_filter *filter, unsigned int flen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a33160)
Location: net/core/filter.c:1051
Inline: False
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
ffffffff81a33160-ffffffff81a332ed: bpf_check_classic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_check_classic(const struct sock_filter *filter, unsigned int flen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a16700)
Location: net/core/filter.c:1051
Inline: False
Direct callers:
  - net/core/filter.c:bpf_prepare_filter
```
**Symbols:**

```
ffffffff81a16700-ffffffff81a16891: bpf_check_classic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int bpf_check_classic(const struct sock_filter *filter, unsigned int flen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:1052
Inline: False
Direct callers:
  - net/core/filter.c:bpf_prepare_filter
```
**Symbols:**

```
ffffffff81ac7c40-ffffffff81ac7e92: bpf_check_classic (STB_LOCAL)
ffffffff81d3716f-ffffffff81d371a9: bpf_check_classic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int bpf_check_classic(const struct sock_filter *filter, unsigned int flen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:1053
Inline: False
Direct callers:
  - net/core/filter.c:bpf_prepare_filter
```
**Symbols:**

```
ffffffff81c45300-ffffffff81c4554e: bpf_check_classic (STB_LOCAL)
ffffffff81f03ace-ffffffff81f03af9: bpf_check_classic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int bpf_check_classic(const struct sock_filter *filter, unsigned int flen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:1055
Inline: False
Direct callers:
  - net/core/filter.c:bpf_prepare_filter
```
**Symbols:**

```
ffffffff81df8f80-ffffffff81df91ce: bpf_check_classic (STB_LOCAL)
ffffffff820ac15c-ffffffff820ac187: bpf_check_classic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int bpf_check_classic(const struct sock_filter *filter, unsigned int flen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:1055
Inline: False
Direct callers:
  - net/core/filter.c:bpf_prepare_filter
```
**Symbols:**

```
ffffffff81e6a920-ffffffff81e6ab59: bpf_check_classic (STB_LOCAL)
ffffffff8212d8ad-ffffffff8212d8d8: bpf_check_classic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int bpf_check_classic(const struct sock_filter *filter, unsigned int flen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:1060
Inline: False
Direct callers:
  - net/core/filter.c:bpf_prepare_filter
```
**Symbols:**

```
ffffffff81f298b0-ffffffff81f29ae9: bpf_check_classic (STB_LOCAL)
ffffffff8220f5f2-ffffffff8220f61d: bpf_check_classic.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bff1ec)
Location: net/core/filter.c:1032
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d1ac20)
Location: net/core/filter.c:1032
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000cea704)
Location: net/core/filter.c:1032
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe0007810d8)
Location: net/core/filter.c:1032
Inline: True
```
</details>
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
In net/core/filter.c (ffffffff818fe6fe)
Location: net/core/filter.c:1032
Inline: True
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
In net/core/filter.c (ffffffff818b852e)
Location: net/core/filter.c:1032
Inline: True
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
In net/core/filter.c (ffffffff8194f72e)
Location: net/core/filter.c:1032
Inline: True
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
In net/core/filter.c (ffffffff819710fe)
Location: net/core/filter.c:1032
Inline: True
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
