# Function: <code>arp_format_neigh_entry</code>

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
In net/ipv4/arp.c (ffffffff8178bf9a)
Location: net/ipv4/arp.c:1284
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
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
In net/ipv4/arp.c (ffffffff817f95ca)
Location: net/ipv4/arp.c:1297
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
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
In net/ipv4/arp.c (ffffffff8182a497)
Location: net/ipv4/arp.c:1297
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
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
In net/ipv4/arp.c (ffffffff8184b6b7)
Location: net/ipv4/arp.c:1335
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
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
In net/ipv4/arp.c (ffffffff818cb367)
Location: net/ipv4/arp.c:1341
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
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
In net/ipv4/arp.c (ffffffff819218d6)
Location: net/ipv4/arp.c:1341
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
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
In net/ipv4/arp.c (ffffffff819506f6)
Location: net/ipv4/arp.c:1343
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
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
In net/ipv4/arp.c (ffffffff819b4fb7)
Location: net/ipv4/arp.c:1339
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
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
In net/ipv4/arp.c (ffffffff819ebce7)
Location: net/ipv4/arp.c:1339
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void arp_format_neigh_entry(struct seq_file *seq, struct neighbour *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff81ad9520)
Location: net/ipv4/arp.c:1339
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_seq_show
```
**Symbols:**

```
ffffffff81ad9520-ffffffff81ad96f4: arp_format_neigh_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void arp_format_neigh_entry(struct seq_file *seq, struct neighbour *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff81ae5f80)
Location: net/ipv4/arp.c:1345
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_seq_show
```
**Symbols:**

```
ffffffff81ae5f80-ffffffff81ae614e: arp_format_neigh_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void arp_format_neigh_entry(struct seq_file *seq, struct neighbour *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff81ad1260)
Location: net/ipv4/arp.c:1345
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_seq_show
```
**Symbols:**

```
ffffffff81ad1260-ffffffff81ad142e: arp_format_neigh_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void arp_format_neigh_entry(struct seq_file *seq, struct neighbour *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff81b8fc80)
Location: net/ipv4/arp.c:1345
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_seq_show
```
**Symbols:**

```
ffffffff81b8fc80-ffffffff81b90051: arp_format_neigh_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void arp_format_neigh_entry(struct seq_file *seq, struct neighbour *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff81d21030)
Location: net/ipv4/arp.c:1344
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_seq_show
```
**Symbols:**

```
ffffffff81d21030-ffffffff81d21417: arp_format_neigh_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void arp_format_neigh_entry(struct seq_file *seq, struct neighbour *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff81ee83e0)
Location: net/ipv4/arp.c:1365
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_seq_show
```
**Symbols:**

```
ffffffff81ee83e0-ffffffff81ee87cd: arp_format_neigh_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void arp_format_neigh_entry(struct seq_file *seq, struct neighbour *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff81f47cb0)
Location: net/ipv4/arp.c:1365
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_seq_show
```
**Symbols:**

```
ffffffff81f47cb0-ffffffff81f480b9: arp_format_neigh_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void arp_format_neigh_entry(struct seq_file *seq, struct neighbour *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff8200de00)
Location: net/ipv4/arp.c:1366
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_seq_show
```
**Symbols:**

```
ffffffff8200de00-ffffffff8200e20f: arp_format_neigh_entry (STB_LOCAL)
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
In net/ipv4/arp.c (ffff800010ca17f0)
Location: net/ipv4/arp.c:1339
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
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
In net/ipv4/arp.c (c0dae5c4)
Location: net/ipv4/arp.c:1339
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
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
In net/ipv4/arp.c (c000000000db4934)
Location: net/ipv4/arp.c:1339
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
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
In net/ipv4/arp.c (ffffffe0007fddf0)
Location: net/ipv4/arp.c:1339
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
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
In net/ipv4/arp.c (ffffffff8198bb17)
Location: net/ipv4/arp.c:1339
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
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
In net/ipv4/arp.c (ffffffff819455d7)
Location: net/ipv4/arp.c:1339
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
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
In net/ipv4/arp.c (ffffffff819f6327)
Location: net/ipv4/arp.c:1339
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
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
In net/ipv4/arp.c (ffffffff81a00527)
Location: net/ipv4/arp.c:1339
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
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
