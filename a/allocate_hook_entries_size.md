# Function: <code>allocate_hook_entries_size</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct nf_hook_entries *allocate_hook_entries_size(u16 num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff8188bd30)
Location: net/netfilter/core.c:72
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_register_net_hook
  - net/netfilter/core.c:nf_register_net_hook
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
```
**Symbols:**

```
ffffffff8188bd30-ffffffff8188bd6f: allocate_hook_entries_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct nf_hook_entries *allocate_hook_entries_size(u16 num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff818df820)
Location: net/netfilter/core.c:49
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_grow
  - net/netfilter/core.c:nf_hook_entries_grow
```
**Symbols:**

```
ffffffff818df820-ffffffff818df85d: allocate_hook_entries_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct nf_hook_entries *allocate_hook_entries_size(u16 num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff8190c3b0)
Location: net/netfilter/core.c:49
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_grow
  - net/netfilter/core.c:nf_hook_entries_grow
```
**Symbols:**

```
ffffffff8190c3b0-ffffffff8190c3ed: allocate_hook_entries_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct nf_hook_entries *allocate_hook_entries_size(u16 num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff8196df40)
Location: net/netfilter/core.c:50
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_grow
  - net/netfilter/core.c:nf_hook_entries_grow
```
**Symbols:**

```
ffffffff8196df40-ffffffff8196df7d: allocate_hook_entries_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct nf_hook_entries *allocate_hook_entries_size(u16 num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff819a49f0)
Location: net/netfilter/core.c:50
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_grow
  - net/netfilter/core.c:nf_hook_entries_grow
```
**Symbols:**

```
ffffffff819a49f0-ffffffff819a4a2d: allocate_hook_entries_size (STB_LOCAL)
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
In net/netfilter/core.c (ffffffff81a8db01)
Location: net/netfilter/core.c:50
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_grow
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
In net/netfilter/core.c (ffffffff81a97ad1)
Location: net/netfilter/core.c:50
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_grow
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
In net/netfilter/core.c (ffffffff81a82e21)
Location: net/netfilter/core.c:50
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_grow
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
In net/netfilter/core.c (ffffffff81b3ca72)
Location: net/netfilter/core.c:50
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_grow
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
In net/netfilter/core.c (ffffffff81cc94d3)
Location: net/netfilter/core.c:50
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_grow
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
In net/netfilter/core.c (ffffffff81e890a3)
Location: net/netfilter/core.c:50
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_grow
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
In net/netfilter/core.c (ffffffff81ee7093)
Location: net/netfilter/core.c:50
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_grow
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
In net/netfilter/core.c (ffffffff81faaea3)
Location: net/netfilter/core.c:50
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_grow
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
struct nf_hook_entries *allocate_hook_entries_size(u16 num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffff800010c53de0)
Location: net/netfilter/core.c:50
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_grow
  - net/netfilter/core.c:nf_hook_entries_grow
```
**Symbols:**

```
ffff800010c53de0-ffff800010c53e2c: allocate_hook_entries_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct nf_hook_entries *allocate_hook_entries_size(u16 num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (c0d63824)
Location: net/netfilter/core.c:50
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_grow
  - net/netfilter/core.c:nf_hook_entries_grow
```
**Symbols:**

```
c0d63824-c0d6386c: allocate_hook_entries_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct nf_hook_entries *allocate_hook_entries_size(u16 num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (c000000000d536f0)
Location: net/netfilter/core.c:50
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_grow
  - net/netfilter/core.c:nf_hook_entries_grow
```
**Symbols:**

```
c000000000d536f0-c000000000d53780: allocate_hook_entries_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct nf_hook_entries *allocate_hook_entries_size(u16 num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffe0007be5f0)
Location: net/netfilter/core.c:50
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_grow
  - net/netfilter/core.c:nf_hook_entries_grow
```
**Symbols:**

```
ffffffe0007be5f0-ffffffe0007be636: allocate_hook_entries_size (STB_LOCAL)
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
struct nf_hook_entries *allocate_hook_entries_size(u16 num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81944860)
Location: net/netfilter/core.c:50
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_grow
  - net/netfilter/core.c:nf_hook_entries_grow
```
**Symbols:**

```
ffffffff81944860-ffffffff8194489d: allocate_hook_entries_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct nf_hook_entries *allocate_hook_entries_size(u16 num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff818fe350)
Location: net/netfilter/core.c:50
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_grow
  - net/netfilter/core.c:nf_hook_entries_grow
```
**Symbols:**

```
ffffffff818fe350-ffffffff818fe38d: allocate_hook_entries_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct nf_hook_entries *allocate_hook_entries_size(u16 num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff819959f0)
Location: net/netfilter/core.c:50
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_grow
  - net/netfilter/core.c:nf_hook_entries_grow
```
**Symbols:**

```
ffffffff819959f0-ffffffff81995a2d: allocate_hook_entries_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct nf_hook_entries *allocate_hook_entries_size(u16 num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff819b85d0)
Location: net/netfilter/core.c:50
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_grow
  - net/netfilter/core.c:nf_hook_entries_grow
```
**Symbols:**

```
ffffffff819b85d0-ffffffff819b860d: allocate_hook_entries_size (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
