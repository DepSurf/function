# Function: <code>netlink_remove</code>

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
In net/netlink/af_netlink.c (ffffffff8174de06)
Location: net/netlink/af_netlink.c:1147
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
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
In net/netlink/af_netlink.c (ffffffff817b9fb6)
Location: net/netlink/af_netlink.c:533
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void netlink_remove(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817e9920)
Location: net/netlink/af_netlink.c:540
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_release
```
**Symbols:**

```
ffffffff817e9920-ffffffff817e9ab0: netlink_remove (STB_LOCAL)
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
In net/netlink/af_netlink.c (ffffffff81809626)
Location: net/netlink/af_netlink.c:571
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
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
In net/netlink/af_netlink.c (ffffffff81888576)
Location: net/netlink/af_netlink.c:573
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
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
In net/netlink/af_netlink.c (ffffffff818dbf96)
Location: net/netlink/af_netlink.c:607
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
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
In net/netlink/af_netlink.c (ffffffff81908966)
Location: net/netlink/af_netlink.c:602
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void netlink_remove(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/netlink/af_netlink.c (0)
Location: net/netlink/af_netlink.c:593
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_release
```
**Symbols:**

```
ffffffff81969c20-ffffffff81969e48: netlink_remove (STB_LOCAL)
ffffffff8196b121-ffffffff8196b134: netlink_remove.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void netlink_remove(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff819a0690)
Location: net/netlink/af_netlink.c:593
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_release
```
**Symbols:**

```
ffffffff819a0690-ffffffff819a08bf: netlink_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void netlink_remove(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a79ee0)
Location: net/netlink/af_netlink.c:593
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_release
```
**Symbols:**

```
ffffffff81a79ee0-ffffffff81a7a039: netlink_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void netlink_remove(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a82d40)
Location: net/netlink/af_netlink.c:594
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_release
```
**Symbols:**

```
ffffffff81a82d40-ffffffff81a82ea0: netlink_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void netlink_remove(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a6be10)
Location: net/netlink/af_netlink.c:604
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_release
```
**Symbols:**

```
ffffffff81a6be10-ffffffff81a6bf70: netlink_remove (STB_LOCAL)
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
In net/netlink/af_netlink.c (ffffffff81b254a2)
Location: net/netlink/af_netlink.c:607
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
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
In net/netlink/af_netlink.c (ffffffff81cadfec)
Location: net/netlink/af_netlink.c:611
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
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
In net/netlink/af_netlink.c (ffffffff81e6b5bc)
Location: net/netlink/af_netlink.c:613
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
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
In net/netlink/af_netlink.c (ffffffff81ec75fc)
Location: net/netlink/af_netlink.c:613
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
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
In net/netlink/af_netlink.c (ffffffff81f8a93c)
Location: net/netlink/af_netlink.c:611
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
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
void netlink_remove(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffff800010c4ed28)
Location: net/netlink/af_netlink.c:593
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_release
```
**Symbols:**

```
ffff800010c4ed28-ffff800010c4eff4: netlink_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void netlink_remove(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c0d5edcc)
Location: net/netlink/af_netlink.c:593
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_release
```
**Symbols:**

```
c0d5edcc-c0d5f17c: netlink_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void netlink_remove(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c000000000d4d3c0)
Location: net/netlink/af_netlink.c:593
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_release
```
**Symbols:**

```
c000000000d4d3c0-c000000000d4d710: netlink_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void netlink_remove(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffe0007baad6)
Location: net/netlink/af_netlink.c:593
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_release
```
**Symbols:**

```
ffffffe0007baad6-ffffffe0007bacde: netlink_remove (STB_LOCAL)
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
void netlink_remove(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81940500)
Location: net/netlink/af_netlink.c:593
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_release
```
**Symbols:**

```
ffffffff81940500-ffffffff8194072f: netlink_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void netlink_remove(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818f9ff0)
Location: net/netlink/af_netlink.c:593
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_release
```
**Symbols:**

```
ffffffff818f9ff0-ffffffff818fa21f: netlink_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void netlink_remove(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81991690)
Location: net/netlink/af_netlink.c:593
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_release
```
**Symbols:**

```
ffffffff81991690-ffffffff819918bf: netlink_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void netlink_remove(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff819b4110)
Location: net/netlink/af_netlink.c:593
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_release
```
**Symbols:**

```
ffffffff819b4110-ffffffff819b43a6: netlink_remove (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
