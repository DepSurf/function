# Function: <code>nf_hook_entries_free</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netfilter/core.c (ffffffff818e0041)
Location: net/netfilter/core.c:74
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
Direct callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
```
**Symbols:**

```
ffffffff818dfe40-ffffffff818dfe70: nf_hook_entries_free.part.8 (STB_LOCAL)
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
In net/netfilter/core.c (ffffffff8190ca51)
Location: net/netfilter/core.c:74
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
Direct callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
```
**Symbols:**

```
ffffffff8190c9b0-ffffffff8190c9e0: nf_hook_entries_free.part.8 (STB_LOCAL)
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
In net/netfilter/core.c (ffffffff8196e578)
Location: net/netfilter/core.c:75
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
Direct callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
```
**Symbols:**

```
ffffffff8196e4f0-ffffffff8196e520: nf_hook_entries_free.part.0 (STB_LOCAL)
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
In net/netfilter/core.c (ffffffff819a4fb8)
Location: net/netfilter/core.c:75
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
Direct callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
```
**Symbols:**

```
ffffffff819a4f30-ffffffff819a4f60: nf_hook_entries_free.part.0 (STB_LOCAL)
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
In net/netfilter/core.c (ffffffff81a8e6a3)
Location: net/netfilter/core.c:75
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
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
In net/netfilter/core.c (ffffffff81a98483)
Location: net/netfilter/core.c:75
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
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
In net/netfilter/core.c (ffffffff81a837d3)
Location: net/netfilter/core.c:75
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
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
In net/netfilter/core.c (ffffffff81b3d443)
Location: net/netfilter/core.c:75
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:nf_hook_entries_insert_raw
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
In net/netfilter/core.c (ffffffff81cc99eb)
Location: net/netfilter/core.c:75
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:nf_hook_entries_insert_raw
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
In net/netfilter/core.c (ffffffff81e895eb)
Location: net/netfilter/core.c:75
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:nf_hook_entries_insert_raw
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
In net/netfilter/core.c (ffffffff81ee75db)
Location: net/netfilter/core.c:75
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:nf_hook_entries_insert_raw
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
In net/netfilter/core.c (ffffffff81fab3eb)
Location: net/netfilter/core.c:75
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:nf_hook_entries_insert_raw
  - net/netfilter/core.c:nf_hook_entries_insert_raw
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
In net/netfilter/core.c (ffff800010c544a0)
Location: net/netfilter/core.c:75
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
Direct callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
```
**Symbols:**

```
ffff800010c543d0-ffff800010c54418: nf_hook_entries_free.part.0 (STB_LOCAL)
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
In net/netfilter/core.c (c0d641b0)
Location: net/netfilter/core.c:75
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
Direct callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
```
**Symbols:**

```
c0d640f0-c0d64130: nf_hook_entries_free.part.0 (STB_LOCAL)
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
In net/netfilter/core.c (c000000000d5427c)
Location: net/netfilter/core.c:75
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:nf_hook_entries_insert_raw
Direct callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:nf_hook_entries_insert_raw
```
**Symbols:**

```
c000000000d540a0-c000000000d540fc: nf_hook_entries_free.part.0 (STB_LOCAL)
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
In net/netfilter/core.c (ffffffe0007beb82)
Location: net/netfilter/core.c:75
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
Direct callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
```
**Symbols:**

```
ffffffe0007beaca-ffffffe0007beb0e: nf_hook_entries_free.part.0 (STB_LOCAL)
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
In net/netfilter/core.c (ffffffff81944e28)
Location: net/netfilter/core.c:75
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
Direct callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
```
**Symbols:**

```
ffffffff81944da0-ffffffff81944dd0: nf_hook_entries_free.part.0 (STB_LOCAL)
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
In net/netfilter/core.c (ffffffff818fe918)
Location: net/netfilter/core.c:75
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
Direct callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
```
**Symbols:**

```
ffffffff818fe890-ffffffff818fe8c0: nf_hook_entries_free.part.0 (STB_LOCAL)
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
In net/netfilter/core.c (ffffffff81995fb8)
Location: net/netfilter/core.c:75
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
Direct callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
```
**Symbols:**

```
ffffffff81995f30-ffffffff81995f60: nf_hook_entries_free.part.0 (STB_LOCAL)
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
In net/netfilter/core.c (ffffffff819b8b88)
Location: net/netfilter/core.c:75
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
Direct callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
```
**Symbols:**

```
ffffffff819b8b00-ffffffff819b8b30: nf_hook_entries_free.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
