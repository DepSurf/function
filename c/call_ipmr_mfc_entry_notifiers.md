# Function: <code>call_ipmr_mfc_entry_notifiers</code>

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
int call_ipmr_mfc_entry_notifiers(struct net *net, enum fib_event_type event_type, struct mfc_cache *mfc, u32 tb_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff818e84c0)
Location: net/ipv4/ipmr.c:680
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff818e84c0-ffffffff818e8569: call_ipmr_mfc_entry_notifiers (STB_LOCAL)
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
In net/ipv4/ipmr.c (ffffffff8194227f)
Location: net/ipv4/ipmr.c:658
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
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
In net/ipv4/ipmr.c (ffffffff8197207c)
Location: net/ipv4/ipmr.c:661
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
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
In net/ipv4/ipmr.c (ffffffff819dbab9)
Location: net/ipv4/ipmr.c:655
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
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
In net/ipv4/ipmr.c (ffffffff81a129e9)
Location: net/ipv4/ipmr.c:655
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
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
In net/ipv4/ipmr.c (ffffffff81b03e7b)
Location: net/ipv4/ipmr.c:629
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
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
In net/ipv4/ipmr.c (ffffffff81b11ff0)
Location: net/ipv4/ipmr.c:629
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
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
In net/ipv4/ipmr.c (ffffffff81aff732)
Location: net/ipv4/ipmr.c:629
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
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
In net/ipv4/ipmr.c (ffffffff81bc14c6)
Location: net/ipv4/ipmr.c:631
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
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
In net/ipv4/ipmr.c (ffffffff81d569ff)
Location: net/ipv4/ipmr.c:624
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
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
In net/ipv4/ipmr.c (ffffffff81f212cf)
Location: net/ipv4/ipmr.c:634
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
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
In net/ipv4/ipmr.c (ffffffff81f8056e)
Location: net/ipv4/ipmr.c:634
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
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
In net/ipv4/ipmr.c (ffffffff82046bee)
Location: net/ipv4/ipmr.c:634
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
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
In net/ipv4/ipmr.c (ffff800010ccc070)
Location: net/ipv4/ipmr.c:655
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
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
In net/ipv4/ipmr.c (c0dd7f40)
Location: net/ipv4/ipmr.c:655
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
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
In net/ipv4/ipmr.c (c000000000deb568)
Location: net/ipv4/ipmr.c:655
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
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
In net/ipv4/ipmr.c (ffffffe0008209b6)
Location: net/ipv4/ipmr.c:655
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
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
In net/ipv4/ipmr.c (ffffffff819b22a9)
Location: net/ipv4/ipmr.c:655
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
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
In net/ipv4/ipmr.c (ffffffff8196e8d9)
Location: net/ipv4/ipmr.c:655
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
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
In net/ipv4/ipmr.c (ffffffff81a1cb49)
Location: net/ipv4/ipmr.c:655
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
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
In net/ipv4/ipmr.c (ffffffff81a27a81)
Location: net/ipv4/ipmr.c:655
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
