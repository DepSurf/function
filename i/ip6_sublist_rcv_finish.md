# Function: <code>ip6_sublist_rcv_finish</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff819997a7)
Location: net/ipv6/ip6_input.c:79
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
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
In net/ipv6/ip6_input.c (ffffffff81a0561b)
Location: net/ipv6/ip6_input.c:79
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ip6_sublist_rcv_finish(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81a3b960)
Location: net/ipv6/ip6_input.c:79
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
```
**Symbols:**

```
ffffffff81a3b960-ffffffff81a3b9ad: ip6_sublist_rcv_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ip6_sublist_rcv_finish(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81b30f30)
Location: net/ipv6/ip6_input.c:79
Inline: False
```
**Symbols:**

```
ffffffff81b30f30-ffffffff81b30f7d: ip6_sublist_rcv_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ip6_sublist_rcv_finish(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81b3fb60)
Location: net/ipv6/ip6_input.c:79
Inline: False
```
**Symbols:**

```
ffffffff81b3fb60-ffffffff81b3fbad: ip6_sublist_rcv_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ip6_sublist_rcv_finish(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81b2e740)
Location: net/ipv6/ip6_input.c:79
Inline: False
```
**Symbols:**

```
ffffffff81b2e740-ffffffff81b2e7b0: ip6_sublist_rcv_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ip6_sublist_rcv_finish(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81bf4a50)
Location: net/ipv6/ip6_input.c:79
Inline: False
```
**Symbols:**

```
ffffffff81bf4a50-ffffffff81bf4ac0: ip6_sublist_rcv_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ip6_sublist_rcv_finish(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81d8d830)
Location: net/ipv6/ip6_input.c:82
Inline: False
```
**Symbols:**

```
ffffffff81d8d830-ffffffff81d8d8a8: ip6_sublist_rcv_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ip6_sublist_rcv_finish(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81f5b950)
Location: net/ipv6/ip6_input.c:82
Inline: False
```
**Symbols:**

```
ffffffff81f5b950-ffffffff81f5b9c8: ip6_sublist_rcv_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ip6_sublist_rcv_finish(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81fbb710)
Location: net/ipv6/ip6_input.c:82
Inline: False
```
**Symbols:**

```
ffffffff81fbb710-ffffffff81fbb788: ip6_sublist_rcv_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ip6_sublist_rcv_finish(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff82088b40)
Location: net/ipv6/ip6_input.c:82
Inline: False
```
**Symbols:**

```
ffffffff82088b40-ffffffff82088bb8: ip6_sublist_rcv_finish (STB_LOCAL)
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
void ip6_sublist_rcv_finish(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffff800010cfcc98)
Location: net/ipv6/ip6_input.c:79
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
```
**Symbols:**

```
ffff800010cfcc98-ffff800010cfccfc: ip6_sublist_rcv_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ip6_sublist_rcv_finish(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (c0e04010)
Location: net/ipv6/ip6_input.c:79
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
```
**Symbols:**

```
c0e04010-c0e04070: ip6_sublist_rcv_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ip6_sublist_rcv_finish(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (c000000000e24890)
Location: net/ipv6/ip6_input.c:79
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
```
**Symbols:**

```
c000000000e24890-c000000000e24934: ip6_sublist_rcv_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ip6_sublist_rcv_finish(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffe000847300)
Location: net/ipv6/ip6_input.c:79
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
```
**Symbols:**

```
ffffffe000847300-ffffffe000847348: ip6_sublist_rcv_finish (STB_LOCAL)
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
void ip6_sublist_rcv_finish(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff819daff0)
Location: net/ipv6/ip6_input.c:79
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
```
**Symbols:**

```
ffffffff819daff0-ffffffff819db03d: ip6_sublist_rcv_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ip6_sublist_rcv_finish(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81997db0)
Location: net/ipv6/ip6_input.c:79
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
```
**Symbols:**

```
ffffffff81997db0-ffffffff81997dfd: ip6_sublist_rcv_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ip6_sublist_rcv_finish(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81a45a70)
Location: net/ipv6/ip6_input.c:79
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
```
**Symbols:**

```
ffffffff81a45a70-ffffffff81a45abd: ip6_sublist_rcv_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ip6_sublist_rcv_finish(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81a51740)
Location: net/ipv6/ip6_input.c:79
Inline: False
Direct callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
```
**Symbols:**

```
ffffffff81a51740-ffffffff81a5178d: ip6_sublist_rcv_finish (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
