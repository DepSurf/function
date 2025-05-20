# Function: <code>__seg6_hmac_fill_info</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6.c (ffffffff81899897)
Location: net/ipv6/seg6.c:234
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
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
In net/ipv6/seg6.c (ffffffff818bfa9f)
Location: net/ipv6/seg6.c:237
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
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
In net/ipv6/seg6.c (ffffffff81942b6b)
Location: net/ipv6/seg6.c:237
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
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
In net/ipv6/seg6.c (ffffffff8199ba9d)
Location: net/ipv6/seg6.c:236
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
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
In net/ipv6/seg6.c (ffffffff819d266d)
Location: net/ipv6/seg6.c:235
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
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
In net/ipv6/seg6.c (ffffffff81a4145a)
Location: net/ipv6/seg6.c:230
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
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
In net/ipv6/seg6.c (ffffffff81a780da)
Location: net/ipv6/seg6.c:230
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __seg6_hmac_fill_info(struct seg6_hmac_info *hinfo, struct sk_buff *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6.c (ffffffff81b71ef0)
Location: net/ipv6/seg6.c:240
Inline: False
Direct callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
**Symbols:**

```
ffffffff81b71ef0-ffffffff81b71fb8: __seg6_hmac_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __seg6_hmac_fill_info(struct seg6_hmac_info *hinfo, struct sk_buff *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6.c (ffffffff81b80c50)
Location: net/ipv6/seg6.c:240
Inline: False
Direct callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
**Symbols:**

```
ffffffff81b80c50-ffffffff81b80d18: __seg6_hmac_fill_info (STB_LOCAL)
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
In net/ipv6/seg6.c (ffffffff81b6fa0a)
Location: net/ipv6/seg6.c:237
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
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
In net/ipv6/seg6.c (ffffffff81c37b5a)
Location: net/ipv6/seg6.c:296
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
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
In net/ipv6/seg6.c (ffffffff81dd571c)
Location: net/ipv6/seg6.c:296
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
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
In net/ipv6/seg6.c (ffffffff81fa6eac)
Location: net/ipv6/seg6.c:301
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
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
In net/ipv6/seg6.c (ffffffff8200770c)
Location: net/ipv6/seg6.c:301
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
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
In net/ipv6/seg6.c (ffffffff820d659c)
Location: net/ipv6/seg6.c:301
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
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
In net/ipv6/seg6.c (ffff800010d4167c)
Location: net/ipv6/seg6.c:230
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
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
In net/ipv6/seg6.c (c0e44064)
Location: net/ipv6/seg6.c:230
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
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
In net/ipv6/seg6.c (c000000000e75ee8)
Location: net/ipv6/seg6.c:230
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
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
In net/ipv6/seg6.c (ffffffe00087cd56)
Location: net/ipv6/seg6.c:230
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
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
In net/ipv6/seg6.c (ffffffff81a1776a)
Location: net/ipv6/seg6.c:230
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
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
In net/ipv6/seg6.c (ffffffff819d452a)
Location: net/ipv6/seg6.c:230
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
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
In net/ipv6/seg6.c (ffffffff81a821ea)
Location: net/ipv6/seg6.c:230
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
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
In net/ipv6/seg6.c (ffffffff81a8eafa)
Location: net/ipv6/seg6.c:230
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
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
