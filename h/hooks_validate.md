# Function: <code>hooks_validate</code>

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
void hooks_validate(const struct nf_hook_entries *hooks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff8188bcb0)
Location: net/netfilter/core.c:160
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_register_net_hook
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
```
**Symbols:**

```
ffffffff8188bcb0-ffffffff8188bd22: hooks_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void hooks_validate(const struct nf_hook_entries *hooks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff818df6f0)
Location: net/netfilter/core.c:163
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
```
**Symbols:**

```
ffffffff818df6f0-ffffffff818df760: hooks_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void hooks_validate(const struct nf_hook_entries *hooks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff8190c250)
Location: net/netfilter/core.c:163
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
```
**Symbols:**

```
ffffffff8190c250-ffffffff8190c2c0: hooks_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void hooks_validate(const struct nf_hook_entries *hooks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/netfilter/core.c (0)
Location: net/netfilter/core.c:164
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
```
**Symbols:**

```
ffffffff8196e0f0-ffffffff8196e155: hooks_validate (STB_LOCAL)
ffffffff8196ea00-ffffffff8196ea1a: hooks_validate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void hooks_validate(const struct nf_hook_entries *hooks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff819a48e0)
Location: net/netfilter/core.c:164
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
```
**Symbols:**

```
ffffffff819a48e0-ffffffff819a492d: hooks_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void hooks_validate(const struct nf_hook_entries *hooks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81a8d980)
Location: net/netfilter/core.c:164
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
```
**Symbols:**

```
ffffffff81a8d980-ffffffff81a8d9cc: hooks_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void hooks_validate(const struct nf_hook_entries *hooks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81a97910)
Location: net/netfilter/core.c:164
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
```
**Symbols:**

```
ffffffff81a97910-ffffffff81a9795c: hooks_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void hooks_validate(const struct nf_hook_entries *hooks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81a82c60)
Location: net/netfilter/core.c:164
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
```
**Symbols:**

```
ffffffff81a82c60-ffffffff81a82cac: hooks_validate (STB_LOCAL)
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
In net/netfilter/core.c (ffffffff81b3d591)
Location: net/netfilter/core.c:164
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_insert_raw
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
In net/netfilter/core.c (ffffffff81cc9b5f)
Location: net/netfilter/core.c:164
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_insert_raw
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
In net/netfilter/core.c (ffffffff81e8977f)
Location: net/netfilter/core.c:164
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_insert_raw
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
In net/netfilter/core.c (ffffffff81ee778e)
Location: net/netfilter/core.c:176
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_insert_raw
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
In net/netfilter/core.c (ffffffff81fab59e)
Location: net/netfilter/core.c:176
Inline: True
Inline callers:
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_insert_raw
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
void hooks_validate(const struct nf_hook_entries *hooks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffff800010c53c18)
Location: net/netfilter/core.c:164
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
```
**Symbols:**

```
ffff800010c53c18-ffff800010c53ca4: hooks_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void hooks_validate(const struct nf_hook_entries *hooks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (c0d63a04)
Location: net/netfilter/core.c:164
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
```
**Symbols:**

```
c0d63a04-c0d63a9c: hooks_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void hooks_validate(const struct nf_hook_entries *hooks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (c000000000d535f0)
Location: net/netfilter/core.c:164
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
  - net/netfilter/core.c:nf_hook_entries_insert_raw
```
**Symbols:**

```
c000000000d535f0-c000000000d53684: hooks_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void hooks_validate(const struct nf_hook_entries *hooks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffe0007be422)
Location: net/netfilter/core.c:164
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
```
**Symbols:**

```
ffffffe0007be422-ffffffe0007be482: hooks_validate (STB_LOCAL)
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
void hooks_validate(const struct nf_hook_entries *hooks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81944750)
Location: net/netfilter/core.c:164
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
```
**Symbols:**

```
ffffffff81944750-ffffffff8194479d: hooks_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void hooks_validate(const struct nf_hook_entries *hooks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff818fe240)
Location: net/netfilter/core.c:164
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
```
**Symbols:**

```
ffffffff818fe240-ffffffff818fe28d: hooks_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void hooks_validate(const struct nf_hook_entries *hooks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff819958e0)
Location: net/netfilter/core.c:164
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
```
**Symbols:**

```
ffffffff819958e0-ffffffff8199592d: hooks_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void hooks_validate(const struct nf_hook_entries *hooks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff819b84c0)
Location: net/netfilter/core.c:164
Inline: False
Direct callers:
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:__nf_hook_entries_try_shrink
```
**Symbols:**

```
ffffffff819b84c0-ffffffff819b850d: hooks_validate (STB_LOCAL)
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
