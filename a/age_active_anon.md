# Function: <code>age_active_anon</code>

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
In mm/vmscan.c (ffffffff811a5b2a)
Location: mm/vmscan.c:2940
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
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
In mm/vmscan.c (ffffffff811bc445)
Location: mm/vmscan.c:3059
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
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
In mm/vmscan.c (ffffffff811ccb0a)
Location: mm/vmscan.c:3070
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
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
In mm/vmscan.c (ffffffff811d57e9)
Location: mm/vmscan.c:3138
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
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
In mm/vmscan.c (ffffffff811eabe3)
Location: mm/vmscan.c:3162
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
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
In mm/vmscan.c (ffffffff8120c3e2)
Location: mm/vmscan.c:3171
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
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
In mm/vmscan.c (ffffffff8121f143)
Location: mm/vmscan.c:3354
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
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
In mm/vmscan.c (ffffffff8122e918)
Location: mm/vmscan.c:3312
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
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
In mm/vmscan.c (ffffffff8123caa8)
Location: mm/vmscan.c:3398
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void age_active_anon(struct pglist_data *pgdat, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81269670)
Location: mm/vmscan.c:3368
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
```
**Symbols:**

```
ffffffff81269670-ffffffff81269751: age_active_anon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void age_active_anon(struct pglist_data *pgdat, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81274160)
Location: mm/vmscan.c:3366
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
```
**Symbols:**

```
ffffffff81274160-ffffffff81274250: age_active_anon (STB_LOCAL)
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
In mm/vmscan.c (ffffffff81279639)
Location: mm/vmscan.c:3564
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
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
In mm/vmscan.c (ffffffff812b74b1)
Location: mm/vmscan.c:3721
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
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
In mm/vmscan.c (ffffffff81312217)
Location: mm/vmscan.c:3864
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
```
</details>
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffff8000102cdd5c)
Location: mm/vmscan.c:3398
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
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
In mm/vmscan.c (c04f7bf4)
Location: mm/vmscan.c:3398
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
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
In mm/vmscan.c (c00000000038b958)
Location: mm/vmscan.c:3398
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
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
In mm/vmscan.c (ffffffe0001ec062)
Location: mm/vmscan.c:3398
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
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
In mm/vmscan.c (ffffffff812350f8)
Location: mm/vmscan.c:3398
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
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
In mm/vmscan.c (ffffffff81228168)
Location: mm/vmscan.c:3398
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
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
In mm/vmscan.c (ffffffff81232e98)
Location: mm/vmscan.c:3398
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
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
In mm/vmscan.c (ffffffff812423a8)
Location: mm/vmscan.c:3398
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
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
</ul>
