# Function: <code>ipmr_mfc_seq_next</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision ⚠️</summary>

```c
void *ipmr_mfc_seq_next(struct seq_file *seq, void *v, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff817a7bc0)
Location: net/ipv4/ipmr.c:2578
Inline: False
```
```
In net/ipv6/ip6mr.c (ffffffff817f89a0)
Location: net/ipv6/ip6mr.c:502
Inline: False
```
**Symbols:**

```
ffffffff817a7bc0-ffffffff817a7c91: ipmr_mfc_seq_next (STB_LOCAL)
ffffffff817f89a0-ffffffff817f8a82: ipmr_mfc_seq_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
void *ipmr_mfc_seq_next(struct seq_file *seq, void *v, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff818158a0)
Location: net/ipv4/ipmr.c:2633
Inline: False
```
```
In net/ipv6/ip6mr.c (ffffffff81868190)
Location: net/ipv6/ip6mr.c:502
Inline: False
```
**Symbols:**

```
ffffffff818158a0-ffffffff81815983: ipmr_mfc_seq_next (STB_LOCAL)
ffffffff81868190-ffffffff81868280: ipmr_mfc_seq_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
void *ipmr_mfc_seq_next(struct seq_file *seq, void *v, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81847060)
Location: net/ipv4/ipmr.c:2644
Inline: False
```
```
In net/ipv6/ip6mr.c (ffffffff8189aff0)
Location: net/ipv6/ip6mr.c:502
Inline: False
```
**Symbols:**

```
ffffffff81847060-ffffffff8184713d: ipmr_mfc_seq_next (STB_LOCAL)
ffffffff8189aff0-ffffffff8189b0da: ipmr_mfc_seq_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
void *ipmr_mfc_seq_next(struct seq_file *seq, void *v, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81868ab0)
Location: net/ipv4/ipmr.c:2937
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff818c0ef0)
Location: net/ipv6/ip6mr.c:503
Inline: False
```
**Symbols:**

```
ffffffff81868ab0-ffffffff81868b35: ipmr_mfc_seq_next (STB_LOCAL)
ffffffff818c0ef0-ffffffff818c0fda: ipmr_mfc_seq_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
void *ipmr_mfc_seq_next(struct seq_file *seq, void *v, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff818e8e90)
Location: net/ipv4/ipmr.c:3102
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81944110)
Location: net/ipv6/ip6mr.c:503
Inline: False
```
**Symbols:**

```
ffffffff818e8e90-ffffffff818e8f15: ipmr_mfc_seq_next (STB_LOCAL)
ffffffff81944110-ffffffff819441f8: ipmr_mfc_seq_next (STB_LOCAL)
```
</details>
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
