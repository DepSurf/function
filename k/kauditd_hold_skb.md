# Function: <code>kauditd_hold_skb</code>

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
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void kauditd_hold_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81132920)
Location: kernel/audit.c:402
Inline: True
Direct callers:
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_reset
```
**Symbols:**

```
ffffffff81132920-ffffffff811329be: kauditd_hold_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void kauditd_hold_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81134090)
Location: kernel/audit.c:535
Inline: True
```
**Symbols:**

```
ffffffff81134090-ffffffff81134122: kauditd_hold_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void kauditd_hold_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81140e50)
Location: kernel/audit.c:535
Inline: True
```
**Symbols:**

```
ffffffff81140e50-ffffffff81140ee2: kauditd_hold_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kauditd_hold_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (0)
Location: kernel/audit.c:578
Inline: True
```
**Symbols:**

```
ffffffff8114f7f0-ffffffff8114f86f: kauditd_hold_skb (STB_LOCAL)
ffffffff81152493-ffffffff811524af: kauditd_hold_skb.cold.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kauditd_hold_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff8115c520)
Location: kernel/audit.c:574
Inline: True
```
**Symbols:**

```
ffffffff8115c4d0-ffffffff8115c54f: kauditd_hold_skb (STB_LOCAL)
ffffffff8115f13b-ffffffff8115f157: kauditd_hold_skb.cold.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kauditd_hold_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff81168bee)
Location: kernel/audit.c:561
Inline: True
```
**Symbols:**

```
ffffffff81168ba0-ffffffff81168c1d: kauditd_hold_skb (STB_LOCAL)
ffffffff8116b72d-ffffffff8116b746: kauditd_hold_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kauditd_hold_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff81174a8e)
Location: kernel/audit.c:561
Inline: True
```
**Symbols:**

```
ffffffff81174a40-ffffffff81174abd: kauditd_hold_skb (STB_LOCAL)
ffffffff8117760d-ffffffff81177626: kauditd_hold_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kauditd_hold_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff81186afe)
Location: kernel/audit.c:563
Inline: True
```
**Symbols:**

```
ffffffff81186ab0-ffffffff81186b2d: kauditd_hold_skb (STB_LOCAL)
ffffffff8118a281-ffffffff8118a29a: kauditd_hold_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kauditd_hold_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff81183e1e)
Location: kernel/audit.c:568
Inline: True
```
**Symbols:**

```
ffffffff81183dd0-ffffffff81183e4d: kauditd_hold_skb (STB_LOCAL)
ffffffff81be4907-ffffffff81be4920: kauditd_hold_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kauditd_hold_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff81184d4e)
Location: kernel/audit.c:568
Inline: True
```
**Symbols:**

```
ffffffff81184d00-ffffffff81184d7d: kauditd_hold_skb (STB_LOCAL)
ffffffff81bd6768-ffffffff81bd6781: kauditd_hold_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void kauditd_hold_skb(struct sk_buff *skb, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/audit.c (0)
Location: kernel/audit.c:570
Inline: False
```
**Symbols:**

```
ffffffff811ad0a0-ffffffff811ad15e: kauditd_hold_skb (STB_LOCAL)
ffffffff81cb34bb-ffffffff81cb34d5: kauditd_hold_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void kauditd_hold_skb(struct sk_buff *skb, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/audit.c (0)
Location: kernel/audit.c:571
Inline: False
```
**Symbols:**

```
ffffffff811ded30-ffffffff811dee1d: kauditd_hold_skb (STB_LOCAL)
ffffffff81e642ef-ffffffff81e64309: kauditd_hold_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kauditd_hold_skb(struct sk_buff *skb, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff812249c0)
Location: kernel/audit.c:569
Inline: False
```
**Symbols:**

```
ffffffff812249c0-ffffffff81224ac5: kauditd_hold_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kauditd_hold_skb(struct sk_buff *skb, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8123af90)
Location: kernel/audit.c:569
Inline: False
```
**Symbols:**

```
ffffffff8123af90-ffffffff8123b095: kauditd_hold_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kauditd_hold_skb(struct sk_buff *skb, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81254e50)
Location: kernel/audit.c:580
Inline: False
```
**Symbols:**

```
ffffffff81254e50-ffffffff81254f55: kauditd_hold_skb (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void kauditd_hold_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffff8000101e9620)
Location: kernel/audit.c:561
Inline: True
```
**Symbols:**

```
ffff8000101e9620-ffff8000101e96d4: kauditd_hold_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void kauditd_hold_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c0429500)
Location: kernel/audit.c:561
Inline: True
```
**Symbols:**

```
c0429500-c04295b8: kauditd_hold_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void kauditd_hold_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c00000000025a420)
Location: kernel/audit.c:561
Inline: True
```
**Symbols:**

```
c00000000025a420-c00000000025a524: kauditd_hold_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void kauditd_hold_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffe00015e384)
Location: kernel/audit.c:561
Inline: True
```
**Symbols:**

```
ffffffe00015e384-ffffffe00015e43c: kauditd_hold_skb (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kauditd_hold_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff8116d0ae)
Location: kernel/audit.c:561
Inline: True
```
**Symbols:**

```
ffffffff8116d060-ffffffff8116d0dd: kauditd_hold_skb (STB_LOCAL)
ffffffff8116fc2d-ffffffff8116fc46: kauditd_hold_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kauditd_hold_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff8116024e)
Location: kernel/audit.c:561
Inline: True
```
**Symbols:**

```
ffffffff81160200-ffffffff8116027d: kauditd_hold_skb (STB_LOCAL)
ffffffff81162dcd-ffffffff81162de6: kauditd_hold_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kauditd_hold_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff8116ae7e)
Location: kernel/audit.c:561
Inline: True
```
**Symbols:**

```
ffffffff8116ae30-ffffffff8116aead: kauditd_hold_skb (STB_LOCAL)
ffffffff8116d9fd-ffffffff8116da16: kauditd_hold_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kauditd_hold_skb(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff8117868e)
Location: kernel/audit.c:561
Inline: True
```
**Symbols:**

```
ffffffff81178640-ffffffff811786bd: kauditd_hold_skb (STB_LOCAL)
ffffffff8117b1ed-ffffffff8117b206: kauditd_hold_skb.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
