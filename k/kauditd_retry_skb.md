# Function: <code>kauditd_retry_skb</code>

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
In kernel/audit.c (ffffffff81132cd1)
Location: kernel/audit.c:435
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void kauditd_retry_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81133c40)
Location: kernel/audit.c:568
Inline: False
```
**Symbols:**

```
ffffffff81133c40-ffffffff81133c5a: kauditd_retry_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void kauditd_retry_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811409f0)
Location: kernel/audit.c:568
Inline: False
```
**Symbols:**

```
ffffffff811409f0-ffffffff81140a0a: kauditd_retry_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void kauditd_retry_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8114f330)
Location: kernel/audit.c:611
Inline: False
```
**Symbols:**

```
ffffffff8114f330-ffffffff8114f34a: kauditd_retry_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void kauditd_retry_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8115c010)
Location: kernel/audit.c:607
Inline: False
```
**Symbols:**

```
ffffffff8115c010-ffffffff8115c02a: kauditd_retry_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void kauditd_retry_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811686c0)
Location: kernel/audit.c:594
Inline: False
```
**Symbols:**

```
ffffffff811686c0-ffffffff811686da: kauditd_retry_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void kauditd_retry_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81174560)
Location: kernel/audit.c:594
Inline: False
```
**Symbols:**

```
ffffffff81174560-ffffffff8117457a: kauditd_retry_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void kauditd_retry_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81186480)
Location: kernel/audit.c:596
Inline: False
```
**Symbols:**

```
ffffffff81186480-ffffffff8118649a: kauditd_retry_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void kauditd_retry_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81183560)
Location: kernel/audit.c:601
Inline: False
```
**Symbols:**

```
ffffffff81183560-ffffffff8118357a: kauditd_retry_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void kauditd_retry_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81184690)
Location: kernel/audit.c:601
Inline: False
```
**Symbols:**

```
ffffffff81184690-ffffffff811846aa: kauditd_retry_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kauditd_retry_skb(struct sk_buff *skb, int error);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff811ad055)
Location: kernel/audit.c:617
Inline: True
```
**Symbols:**

```
ffffffff811ad020-ffffffff811ad093: kauditd_retry_skb (STB_LOCAL)
ffffffff81cb34a2-ffffffff81cb34bb: kauditd_retry_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kauditd_retry_skb(struct sk_buff *skb, int error);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff811decd1)
Location: kernel/audit.c:618
Inline: True
```
**Symbols:**

```
ffffffff811dec90-ffffffff811ded22: kauditd_retry_skb (STB_LOCAL)
ffffffff81e642d3-ffffffff81e642ef: kauditd_retry_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void kauditd_retry_skb(struct sk_buff *skb, int error);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81224900)
Location: kernel/audit.c:616
Inline: True
```
**Symbols:**

```
ffffffff81224900-ffffffff812249a5: kauditd_retry_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void kauditd_retry_skb(struct sk_buff *skb, int error);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8123aed0)
Location: kernel/audit.c:616
Inline: True
```
**Symbols:**

```
ffffffff8123aed0-ffffffff8123af75: kauditd_retry_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void kauditd_retry_skb(struct sk_buff *skb, int error);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81254d90)
Location: kernel/audit.c:627
Inline: True
```
**Symbols:**

```
ffffffff81254d90-ffffffff81254e35: kauditd_retry_skb (STB_LOCAL)
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
void kauditd_retry_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffff8000101e8f40)
Location: kernel/audit.c:594
Inline: False
```
**Symbols:**

```
ffff8000101e8f40-ffff8000101e8f78: kauditd_retry_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void kauditd_retry_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c0428f50)
Location: kernel/audit.c:594
Inline: False
```
**Symbols:**

```
c0428f50-c0428f78: kauditd_retry_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void kauditd_retry_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c000000000259ae0)
Location: kernel/audit.c:594
Inline: False
```
**Symbols:**

```
c000000000259ae0-c000000000259b20: kauditd_retry_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void kauditd_retry_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffe00015de36)
Location: kernel/audit.c:594
Inline: False
```
**Symbols:**

```
ffffffe00015de36-ffffffe00015de68: kauditd_retry_skb (STB_LOCAL)
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
void kauditd_retry_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116cb80)
Location: kernel/audit.c:594
Inline: False
```
**Symbols:**

```
ffffffff8116cb80-ffffffff8116cb9a: kauditd_retry_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void kauditd_retry_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8115fd20)
Location: kernel/audit.c:594
Inline: False
```
**Symbols:**

```
ffffffff8115fd20-ffffffff8115fd3a: kauditd_retry_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void kauditd_retry_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116a950)
Location: kernel/audit.c:594
Inline: False
```
**Symbols:**

```
ffffffff8116a950-ffffffff8116a96a: kauditd_retry_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void kauditd_retry_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81178110)
Location: kernel/audit.c:594
Inline: False
```
**Symbols:**

```
ffffffff81178110-ffffffff8117812a: kauditd_retry_skb (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int error</code>
</li>
</ul>
</details>
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
