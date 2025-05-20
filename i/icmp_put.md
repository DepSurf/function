# Function: <code>icmp_put</code>

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
In net/ipv4/proc.c (ffffffff817a634c)
Location: net/ipv4/proc.c:351
Inline: True
Inline callers:
  - net/ipv4/proc.c:snmp_seq_show
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
In net/ipv4/proc.c (ffffffff8181402b)
Location: net/ipv4/proc.c:351
Inline: True
Inline callers:
  - net/ipv4/proc.c:snmp_seq_show
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
In net/ipv4/proc.c (ffffffff818455e1)
Location: net/ipv4/proc.c:354
Inline: True
Inline callers:
  - net/ipv4/proc.c:snmp_seq_show
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
In net/ipv4/proc.c (ffffffff8186712c)
Location: net/ipv4/proc.c:354
Inline: True
Inline callers:
  - net/ipv4/proc.c:snmp_seq_show
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
In net/ipv4/proc.c (ffffffff818e737c)
Location: net/ipv4/proc.c:346
Inline: True
Inline callers:
  - net/ipv4/proc.c:snmp_seq_show
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
In net/ipv4/proc.c (ffffffff8193e26c)
Location: net/ipv4/proc.c:336
Inline: True
Inline callers:
  - net/ipv4/proc.c:snmp_seq_show
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
In net/ipv4/proc.c (ffffffff8196e10c)
Location: net/ipv4/proc.c:340
Inline: True
Inline callers:
  - net/ipv4/proc.c:snmp_seq_show
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
In net/ipv4/proc.c (ffffffff819d78f8)
Location: net/ipv4/proc.c:338
Inline: True
Inline callers:
  - net/ipv4/proc.c:snmp_seq_show
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
In net/ipv4/proc.c (ffffffff81a0e3e8)
Location: net/ipv4/proc.c:338
Inline: True
Inline callers:
  - net/ipv4/proc.c:snmp_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void icmp_put(struct seq_file *seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/proc.c (ffffffff81afe8c0)
Location: net/ipv4/proc.c:341
Inline: False
Direct callers:
  - net/ipv4/proc.c:snmp_seq_show
```
**Symbols:**

```
ffffffff81afe8c0-ffffffff81afea5a: icmp_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void icmp_put(struct seq_file *seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/proc.c (ffffffff81b0c930)
Location: net/ipv4/proc.c:344
Inline: False
Direct callers:
  - net/ipv4/proc.c:snmp_seq_show
```
**Symbols:**

```
ffffffff81b0c930-ffffffff81b0caca: icmp_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void icmp_put(struct seq_file *seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/proc.c (ffffffff81afa5a0)
Location: net/ipv4/proc.c:344
Inline: False
Direct callers:
  - net/ipv4/proc.c:snmp_seq_show
```
**Symbols:**

```
ffffffff81afa5a0-ffffffff81afa73a: icmp_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void icmp_put(struct seq_file *seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/proc.c (ffffffff81bbb2a0)
Location: net/ipv4/proc.c:346
Inline: False
Direct callers:
  - net/ipv4/proc.c:snmp_seq_show
```
**Symbols:**

```
ffffffff81bbb2a0-ffffffff81bbb55e: icmp_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void icmp_put(struct seq_file *seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/proc.c (ffffffff81d4f370)
Location: net/ipv4/proc.c:346
Inline: False
Direct callers:
  - net/ipv4/proc.c:snmp_seq_show
```
**Symbols:**

```
ffffffff81d4f370-ffffffff81d4f63e: icmp_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void icmp_put(struct seq_file *seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/proc.c (ffffffff81f18fa0)
Location: net/ipv4/proc.c:347
Inline: False
Direct callers:
  - net/ipv4/proc.c:snmp_seq_show
```
**Symbols:**

```
ffffffff81f18fa0-ffffffff81f1926e: icmp_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void icmp_put(struct seq_file *seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/proc.c (ffffffff81f78c10)
Location: net/ipv4/proc.c:347
Inline: False
Direct callers:
  - net/ipv4/proc.c:snmp_seq_show
```
**Symbols:**

```
ffffffff81f78c10-ffffffff81f78f11: icmp_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void icmp_put(struct seq_file *seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/proc.c (ffffffff8203f2d0)
Location: net/ipv4/proc.c:353
Inline: False
Direct callers:
  - net/ipv4/proc.c:snmp_seq_show
```
**Symbols:**

```
ffffffff8203f2d0-ffffffff8203f5d1: icmp_put (STB_LOCAL)
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
In net/ipv4/proc.c (ffff800010cc80a8)
Location: net/ipv4/proc.c:338
Inline: True
Inline callers:
  - net/ipv4/proc.c:snmp_seq_show
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
In net/ipv4/proc.c (c0dd3508)
Location: net/ipv4/proc.c:338
Inline: True
Inline callers:
  - net/ipv4/proc.c:snmp_seq_show
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
In net/ipv4/proc.c (c000000000de5214)
Location: net/ipv4/proc.c:338
Inline: True
Inline callers:
  - net/ipv4/proc.c:snmp_seq_show
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
In net/ipv4/proc.c (ffffffe00081c4ba)
Location: net/ipv4/proc.c:338
Inline: True
Inline callers:
  - net/ipv4/proc.c:snmp_seq_show
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
In net/ipv4/proc.c (ffffffff819ae188)
Location: net/ipv4/proc.c:338
Inline: True
Inline callers:
  - net/ipv4/proc.c:snmp_seq_show
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
In net/ipv4/proc.c (ffffffff8196a7b8)
Location: net/ipv4/proc.c:338
Inline: True
Inline callers:
  - net/ipv4/proc.c:snmp_seq_show
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
In net/ipv4/proc.c (ffffffff81a18a28)
Location: net/ipv4/proc.c:338
Inline: True
Inline callers:
  - net/ipv4/proc.c:snmp_seq_show
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
In net/ipv4/proc.c (ffffffff81a234a8)
Location: net/ipv4/proc.c:338
Inline: True
Inline callers:
  - net/ipv4/proc.c:snmp_seq_show
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
