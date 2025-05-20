# Function: <code>secpath_dup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sec_path *secpath_dup(struct sec_path *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff817bb7c0)
Location: net/xfrm/xfrm_input.c:105
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
ffffffff817bb7c0-ffffffff817bb84f: secpath_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sec_path *secpath_dup(struct sec_path *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff818286e0)
Location: net/xfrm/xfrm_input.c:105
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
ffffffff818286e0-ffffffff81828771: secpath_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sec_path *secpath_dup(struct sec_path *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff8185a0c0)
Location: net/xfrm/xfrm_input.c:105
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
ffffffff8185a0c0-ffffffff8185a151: secpath_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sec_path *secpath_dup(struct sec_path *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff8187dea0)
Location: net/xfrm/xfrm_input.c:99
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:secpath_set
  - net/xfrm/xfrm_output.c:xfrm_output
```
**Symbols:**

```
ffffffff8187dea0-ffffffff8187df6e: secpath_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sec_path *secpath_dup(struct sec_path *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff818fed40)
Location: net/xfrm/xfrm_input.c:116
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:secpath_set
  - net/xfrm/xfrm_output.c:xfrm_output
```
**Symbols:**

```
ffffffff818fed40-ffffffff818fee18: secpath_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sec_path *secpath_dup(struct sec_path *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81955810)
Location: net/xfrm/xfrm_input.c:123
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:secpath_set
  - net/xfrm/xfrm_output.c:xfrm_output
```
**Symbols:**

```
ffffffff81955810-ffffffff819558df: secpath_dup (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
