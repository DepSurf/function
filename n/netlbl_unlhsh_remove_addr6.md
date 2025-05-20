# Function: <code>netlbl_unlhsh_remove_addr6</code>

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
In net/netlabel/netlabel_unlabeled.c (ffffffff8180f58d)
Location: net/netlabel/netlabel_unlabeled.c:547
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
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
In net/netlabel/netlabel_unlabeled.c (ffffffff81881c3d)
Location: net/netlabel/netlabel_unlabeled.c:547
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
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
In net/netlabel/netlabel_unlabeled.c (ffffffff818b64ed)
Location: net/netlabel/netlabel_unlabeled.c:541
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
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
In net/netlabel/netlabel_unlabeled.c (ffffffff818dcdf9)
Location: net/netlabel/netlabel_unlabeled.c:541
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
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
In net/netlabel/netlabel_unlabeled.c (ffffffff819629e9)
Location: net/netlabel/netlabel_unlabeled.c:541
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
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
In net/netlabel/netlabel_unlabeled.c (ffffffff819bc249)
Location: net/netlabel/netlabel_unlabeled.c:541
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
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
In net/netlabel/netlabel_unlabeled.c (ffffffff819f34ba)
Location: net/netlabel/netlabel_unlabeled.c:541
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
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
In net/netlabel/netlabel_unlabeled.c (ffffffff81a62836)
Location: net/netlabel/netlabel_unlabeled.c:527
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
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
In net/netlabel/netlabel_unlabeled.c (ffffffff81a99416)
Location: net/netlabel/netlabel_unlabeled.c:527
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int netlbl_unlhsh_remove_addr6(struct net *net, struct netlbl_unlhsh_iface *iface, const struct in6_addr *addr, const struct in6_addr *mask, struct netlbl_audit *audit_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b94510)
Location: net/netlabel/netlabel_unlabeled.c:527
Inline: False
Direct callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffffffff81b94510-ffffffff81b946aa: netlbl_unlhsh_remove_addr6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int netlbl_unlhsh_remove_addr6(struct net *net, struct netlbl_unlhsh_iface *iface, const struct in6_addr *addr, const struct in6_addr *mask, struct netlbl_audit *audit_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_unlabeled.c (ffffffff81ba4150)
Location: net/netlabel/netlabel_unlabeled.c:527
Inline: False
Direct callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffffffff81ba4150-ffffffff81ba42ea: netlbl_unlhsh_remove_addr6 (STB_LOCAL)
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
In net/netlabel/netlabel_unlabeled.c (ffffffff81b939db)
Location: net/netlabel/netlabel_unlabeled.c:527
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
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
In net/netlabel/netlabel_unlabeled.c (ffffffff81c6017b)
Location: net/netlabel/netlabel_unlabeled.c:526
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
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
In net/netlabel/netlabel_unlabeled.c (ffffffff81e025f7)
Location: net/netlabel/netlabel_unlabeled.c:526
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
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
In net/netlabel/netlabel_unlabeled.c (ffffffff81fd74e7)
Location: net/netlabel/netlabel_unlabeled.c:526
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
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
In net/netlabel/netlabel_unlabeled.c (ffffffff820531d8)
Location: net/netlabel/netlabel_unlabeled.c:526
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
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
In net/netlabel/netlabel_unlabeled.c (ffffffff821259d8)
Location: net/netlabel/netlabel_unlabeled.c:522
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
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
In net/netlabel/netlabel_unlabeled.c (ffff800010d68cc8)
Location: net/netlabel/netlabel_unlabeled.c:527
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
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
In net/netlabel/netlabel_unlabeled.c (c0e67440)
Location: net/netlabel/netlabel_unlabeled.c:527
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
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
In net/netlabel/netlabel_unlabeled.c (c000000000ea5974)
Location: net/netlabel/netlabel_unlabeled.c:527
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
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
In net/netlabel/netlabel_unlabeled.c (ffffffe00089bef2)
Location: net/netlabel/netlabel_unlabeled.c:527
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
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
In net/netlabel/netlabel_unlabeled.c (ffffffff81a387a6)
Location: net/netlabel/netlabel_unlabeled.c:527
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
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
In net/netlabel/netlabel_unlabeled.c (ffffffff819f53c6)
Location: net/netlabel/netlabel_unlabeled.c:527
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
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
In net/netlabel/netlabel_unlabeled.c (ffffffff81aa4656)
Location: net/netlabel/netlabel_unlabeled.c:527
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
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
In net/netlabel/netlabel_unlabeled.c (ffffffff81ab09f5)
Location: net/netlabel/netlabel_unlabeled.c:527
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
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
