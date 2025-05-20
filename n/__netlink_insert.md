# Function: <code>__netlink_insert</code>

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
In net/netlink/af_netlink.c (ffffffff8174cc38)
Location: net/netlink/af_netlink.c:1056
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
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
In net/netlink/af_netlink.c (ffffffff817b9004)
Location: net/netlink/af_netlink.c:442
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
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
In net/netlink/af_netlink.c (ffffffff817e8ace)
Location: net/netlink/af_netlink.c:449
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
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
In net/netlink/af_netlink.c (ffffffff818080fb)
Location: net/netlink/af_netlink.c:480
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
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
In net/netlink/af_netlink.c (ffffffff81886f41)
Location: net/netlink/af_netlink.c:482
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
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
In net/netlink/af_netlink.c (ffffffff818db065)
Location: net/netlink/af_netlink.c:516
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
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
In net/netlink/af_netlink.c (ffffffff81907982)
Location: net/netlink/af_netlink.c:516
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __netlink_insert(struct netlink_table *table, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81968ba0)
Location: net/netlink/af_netlink.c:507
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_insert
```
**Symbols:**

```
ffffffff81968ba0-ffffffff81968e24: __netlink_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __netlink_insert(struct netlink_table *table, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8199f640)
Location: net/netlink/af_netlink.c:507
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_insert
```
**Symbols:**

```
ffffffff8199f640-ffffffff8199f8c4: __netlink_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a77d7b)
Location: net/netlink/af_netlink.c:507
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a80c4b)
Location: net/netlink/af_netlink.c:508
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
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
In net/netlink/af_netlink.c (ffffffff81a6a2cd)
Location: net/netlink/af_netlink.c:518
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
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
In net/netlink/af_netlink.c (ffffffff81b238cc)
Location: net/netlink/af_netlink.c:518
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
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
In net/netlink/af_netlink.c (ffffffff81cac2eb)
Location: net/netlink/af_netlink.c:522
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
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
In net/netlink/af_netlink.c (ffffffff81e69ecb)
Location: net/netlink/af_netlink.c:522
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
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
In net/netlink/af_netlink.c (ffffffff81ec5e88)
Location: net/netlink/af_netlink.c:522
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
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
In net/netlink/af_netlink.c (ffffffff81f890ec)
Location: net/netlink/af_netlink.c:520
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
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
int __netlink_insert(struct netlink_table *table, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffff800010c4c9a8)
Location: net/netlink/af_netlink.c:507
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_insert
```
**Symbols:**

```
ffff800010c4c9a8-ffff800010c4cc9c: __netlink_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __netlink_insert(struct netlink_table *table, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c0d5da30)
Location: net/netlink/af_netlink.c:507
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_insert
```
**Symbols:**

```
c0d5da30-c0d5de18: __netlink_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __netlink_insert(struct netlink_table *table, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c000000000d4a530)
Location: net/netlink/af_netlink.c:507
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_insert
```
**Symbols:**

```
c000000000d4a530-c000000000d4a920: __netlink_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __netlink_insert(struct netlink_table *table, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffe0007b894c)
Location: net/netlink/af_netlink.c:507
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_insert
```
**Symbols:**

```
ffffffe0007b894c-ffffffe0007b8b98: __netlink_insert (STB_LOCAL)
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
int __netlink_insert(struct netlink_table *table, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8193f4b0)
Location: net/netlink/af_netlink.c:507
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_insert
```
**Symbols:**

```
ffffffff8193f4b0-ffffffff8193f734: __netlink_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __netlink_insert(struct netlink_table *table, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818f8fb0)
Location: net/netlink/af_netlink.c:507
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_insert
```
**Symbols:**

```
ffffffff818f8fb0-ffffffff818f9234: __netlink_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __netlink_insert(struct netlink_table *table, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81990640)
Location: net/netlink/af_netlink.c:507
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_insert
```
**Symbols:**

```
ffffffff81990640-ffffffff819908c4: __netlink_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __netlink_insert(struct netlink_table *table, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff819b2f00)
Location: net/netlink/af_netlink.c:507
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_insert
```
**Symbols:**

```
ffffffff819b2f00-ffffffff819b31ff: __netlink_insert (STB_LOCAL)
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
