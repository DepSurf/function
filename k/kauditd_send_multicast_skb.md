# Function: <code>kauditd_send_multicast_skb</code>

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
In kernel/audit.c (ffffffff81121110)
Location: kernel/audit.c:451
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_end
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
In kernel/audit.c (ffffffff81129050)
Location: kernel/audit.c:448
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_end
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
In kernel/audit.c (ffffffff81132b7b)
Location: kernel/audit.c:499
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
void kauditd_send_multicast_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81133bb0)
Location: kernel/audit.c:744
Inline: False
```
**Symbols:**

```
ffffffff81133bb0-ffffffff81133c3e: kauditd_send_multicast_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void kauditd_send_multicast_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81140960)
Location: kernel/audit.c:744
Inline: False
```
**Symbols:**

```
ffffffff81140960-ffffffff811409ee: kauditd_send_multicast_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void kauditd_send_multicast_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8114f2a0)
Location: kernel/audit.c:787
Inline: False
```
**Symbols:**

```
ffffffff8114f2a0-ffffffff8114f330: kauditd_send_multicast_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void kauditd_send_multicast_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8115bf80)
Location: kernel/audit.c:783
Inline: False
```
**Symbols:**

```
ffffffff8115bf80-ffffffff8115c00d: kauditd_send_multicast_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void kauditd_send_multicast_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81168630)
Location: kernel/audit.c:770
Inline: False
```
**Symbols:**

```
ffffffff81168630-ffffffff811686c0: kauditd_send_multicast_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void kauditd_send_multicast_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811744d0)
Location: kernel/audit.c:770
Inline: False
```
**Symbols:**

```
ffffffff811744d0-ffffffff81174560: kauditd_send_multicast_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void kauditd_send_multicast_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811863f0)
Location: kernel/audit.c:772
Inline: False
```
**Symbols:**

```
ffffffff811863f0-ffffffff81186480: kauditd_send_multicast_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void kauditd_send_multicast_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81183770)
Location: kernel/audit.c:777
Inline: False
```
**Symbols:**

```
ffffffff81183770-ffffffff81183806: kauditd_send_multicast_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void kauditd_send_multicast_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811847e0)
Location: kernel/audit.c:777
Inline: False
```
**Symbols:**

```
ffffffff811847e0-ffffffff81184876: kauditd_send_multicast_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void kauditd_send_multicast_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811acaf0)
Location: kernel/audit.c:799
Inline: False
```
**Symbols:**

```
ffffffff811acaf0-ffffffff811acb86: kauditd_send_multicast_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void kauditd_send_multicast_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811de5e0)
Location: kernel/audit.c:800
Inline: False
```
**Symbols:**

```
ffffffff811de5e0-ffffffff811de6a5: kauditd_send_multicast_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kauditd_send_multicast_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81224170)
Location: kernel/audit.c:798
Inline: False
```
**Symbols:**

```
ffffffff81224170-ffffffff81224235: kauditd_send_multicast_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kauditd_send_multicast_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8123a750)
Location: kernel/audit.c:798
Inline: False
```
**Symbols:**

```
ffffffff8123a750-ffffffff8123a815: kauditd_send_multicast_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kauditd_send_multicast_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81254430)
Location: kernel/audit.c:809
Inline: False
```
**Symbols:**

```
ffffffff81254430-ffffffff81254509: kauditd_send_multicast_skb (STB_LOCAL)
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
void kauditd_send_multicast_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffff8000101e8ea0)
Location: kernel/audit.c:770
Inline: False
```
**Symbols:**

```
ffff8000101e8ea0-ffff8000101e8f40: kauditd_send_multicast_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void kauditd_send_multicast_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c0428ea4)
Location: kernel/audit.c:770
Inline: False
```
**Symbols:**

```
c0428ea4-c0428f50: kauditd_send_multicast_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void kauditd_send_multicast_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c0000000002599f0)
Location: kernel/audit.c:770
Inline: False
```
**Symbols:**

```
c0000000002599f0-c000000000259ad8: kauditd_send_multicast_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void kauditd_send_multicast_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffe00015dd96)
Location: kernel/audit.c:770
Inline: False
```
**Symbols:**

```
ffffffe00015dd96-ffffffe00015de36: kauditd_send_multicast_skb (STB_LOCAL)
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
void kauditd_send_multicast_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116caf0)
Location: kernel/audit.c:770
Inline: False
```
**Symbols:**

```
ffffffff8116caf0-ffffffff8116cb80: kauditd_send_multicast_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void kauditd_send_multicast_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8115fc90)
Location: kernel/audit.c:770
Inline: False
```
**Symbols:**

```
ffffffff8115fc90-ffffffff8115fd20: kauditd_send_multicast_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void kauditd_send_multicast_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116a8c0)
Location: kernel/audit.c:770
Inline: False
```
**Symbols:**

```
ffffffff8116a8c0-ffffffff8116a950: kauditd_send_multicast_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void kauditd_send_multicast_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81178070)
Location: kernel/audit.c:770
Inline: False
```
**Symbols:**

```
ffffffff81178070-ffffffff8117810c: kauditd_send_multicast_skb (STB_LOCAL)
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
