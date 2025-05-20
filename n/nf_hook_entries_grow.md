# Function: <code>nf_hook_entries_grow</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff8188c09e)
Location: net/netfilter/core.c:101
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_register_net_hook
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct nf_hook_entries *nf_hook_entries_grow(const struct nf_hook_entries *old, const struct nf_hook_ops *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff818df860)
Location: net/netfilter/core.c:103
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_register_net_hook
```
**Symbols:**

```
ffffffff818df860-ffffffff818df9c8: nf_hook_entries_grow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct nf_hook_entries *nf_hook_entries_grow(const struct nf_hook_entries *old, const struct nf_hook_ops *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff8190c3f0)
Location: net/netfilter/core.c:103
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_register_net_hook
```
**Symbols:**

```
ffffffff8190c3f0-ffffffff8190c558: nf_hook_entries_grow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct nf_hook_entries *nf_hook_entries_grow(const struct nf_hook_entries *old, const struct nf_hook_ops *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff8196df80)
Location: net/netfilter/core.c:104
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_register_net_hook
```
**Symbols:**

```
ffffffff8196df80-ffffffff8196e0ec: nf_hook_entries_grow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct nf_hook_entries *nf_hook_entries_grow(const struct nf_hook_entries *old, const struct nf_hook_ops *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff819a4a30)
Location: net/netfilter/core.c:104
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_register_net_hook
```
**Symbols:**

```
ffffffff819a4a30-ffffffff819a4b9c: nf_hook_entries_grow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct nf_hook_entries *nf_hook_entries_grow(const struct nf_hook_entries *old, const struct nf_hook_ops *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81a8e170)
Location: net/netfilter/core.c:104
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_register_net_hook
```
**Symbols:**

```
ffffffff81a8e170-ffffffff81a8e325: nf_hook_entries_grow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct nf_hook_entries *nf_hook_entries_grow(const struct nf_hook_entries *old, const struct nf_hook_ops *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81a98160)
Location: net/netfilter/core.c:104
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_register_net_hook
```
**Symbols:**

```
ffffffff81a98160-ffffffff81a98315: nf_hook_entries_grow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct nf_hook_entries *nf_hook_entries_grow(const struct nf_hook_entries *old, const struct nf_hook_ops *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81a834b0)
Location: net/netfilter/core.c:104
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_register_net_hook
```
**Symbols:**

```
ffffffff81a834b0-ffffffff81a83665: nf_hook_entries_grow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct nf_hook_entries *nf_hook_entries_grow(const struct nf_hook_entries *old, const struct nf_hook_ops *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81b3d1a0)
Location: net/netfilter/core.c:104
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:nf_hook_entries_insert_raw
```
**Symbols:**

```
ffffffff81b3d1a0-ffffffff81b3d355: nf_hook_entries_grow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct nf_hook_entries *nf_hook_entries_grow(const struct nf_hook_entries *old, const struct nf_hook_ops *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81cc8e10)
Location: net/netfilter/core.c:104
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:nf_hook_entries_insert_raw
```
**Symbols:**

```
ffffffff81cc8e10-ffffffff81cc9004: nf_hook_entries_grow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct nf_hook_entries *nf_hook_entries_grow(const struct nf_hook_entries *old, const struct nf_hook_ops *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81e88970)
Location: net/netfilter/core.c:104
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:nf_hook_entries_insert_raw
```
**Symbols:**

```
ffffffff81e88970-ffffffff81e88b64: nf_hook_entries_grow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct nf_hook_entries *nf_hook_entries_grow(const struct nf_hook_entries *old, const struct nf_hook_ops *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81ee6900)
Location: net/netfilter/core.c:104
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:nf_hook_entries_insert_raw
```
**Symbols:**

```
ffffffff81ee6900-ffffffff81ee6ada: nf_hook_entries_grow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct nf_hook_entries *nf_hook_entries_grow(const struct nf_hook_entries *old, const struct nf_hook_ops *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81faa6b0)
Location: net/netfilter/core.c:104
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:nf_hook_entries_insert_raw
```
**Symbols:**

```
ffffffff81faa6b0-ffffffff81faa88a: nf_hook_entries_grow (STB_LOCAL)
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
struct nf_hook_entries *nf_hook_entries_grow(const struct nf_hook_entries *old, const struct nf_hook_ops *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffff800010c53e30)
Location: net/netfilter/core.c:104
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_register_net_hook
```
**Symbols:**

```
ffff800010c53e30-ffff800010c53fdc: nf_hook_entries_grow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct nf_hook_entries *nf_hook_entries_grow(const struct nf_hook_entries *old, const struct nf_hook_ops *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (c0d6386c)
Location: net/netfilter/core.c:104
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_register_net_hook
```
**Symbols:**

```
c0d6386c-c0d63a04: nf_hook_entries_grow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct nf_hook_entries *nf_hook_entries_grow(const struct nf_hook_entries *old, const struct nf_hook_ops *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (c000000000d53780)
Location: net/netfilter/core.c:104
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:nf_hook_entries_insert_raw
```
**Symbols:**

```
c000000000d53780-c000000000d53a08: nf_hook_entries_grow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct nf_hook_entries *nf_hook_entries_grow(const struct nf_hook_entries *old, const struct nf_hook_ops *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffe0007be636)
Location: net/netfilter/core.c:104
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_register_net_hook
```
**Symbols:**

```
ffffffe0007be636-ffffffe0007be782: nf_hook_entries_grow (STB_LOCAL)
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
struct nf_hook_entries *nf_hook_entries_grow(const struct nf_hook_entries *old, const struct nf_hook_ops *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff819448a0)
Location: net/netfilter/core.c:104
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_register_net_hook
```
**Symbols:**

```
ffffffff819448a0-ffffffff81944a0c: nf_hook_entries_grow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct nf_hook_entries *nf_hook_entries_grow(const struct nf_hook_entries *old, const struct nf_hook_ops *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff818fe390)
Location: net/netfilter/core.c:104
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_register_net_hook
```
**Symbols:**

```
ffffffff818fe390-ffffffff818fe4fc: nf_hook_entries_grow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct nf_hook_entries *nf_hook_entries_grow(const struct nf_hook_entries *old, const struct nf_hook_ops *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81995a30)
Location: net/netfilter/core.c:104
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_register_net_hook
```
**Symbols:**

```
ffffffff81995a30-ffffffff81995b9c: nf_hook_entries_grow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct nf_hook_entries *nf_hook_entries_grow(const struct nf_hook_entries *old, const struct nf_hook_ops *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff819b8610)
Location: net/netfilter/core.c:104
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_register_net_hook
```
**Symbols:**

```
ffffffff819b8610-ffffffff819b877c: nf_hook_entries_grow (STB_LOCAL)
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
