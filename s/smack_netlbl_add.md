# Function: <code>smack_netlbl_add</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int smack_netlbl_add(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814f1070)
Location: security/smack/smack_lsm.c:2386
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_inode_setsecurity
```
**Symbols:**

```
ffffffff814f1070-ffffffff814f1106: smack_netlbl_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int smack_netlbl_add(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814f89e0)
Location: security/smack/smack_lsm.c:2385
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_inode_setsecurity
```
**Symbols:**

```
ffffffff814f89e0-ffffffff814f8a76: smack_netlbl_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int smack_netlbl_add(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff815535d0)
Location: security/smack/smack_lsm.c:2385
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_inode_setsecurity
```
**Symbols:**

```
ffffffff815535d0-ffffffff81553666: smack_netlbl_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int smack_netlbl_add(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff815eb140)
Location: security/smack/smack_lsm.c:2391
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_inode_setsecurity
```
**Symbols:**

```
ffffffff815eb140-ffffffff815eb1db: smack_netlbl_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int smack_netlbl_add(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8169af40)
Location: security/smack/smack_lsm.c:2466
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_inode_setsecurity
```
**Symbols:**

```
ffffffff8169af40-ffffffff8169afdb: smack_netlbl_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int smack_netlbl_add(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff816d3750)
Location: security/smack/smack_lsm.c:2529
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_inode_setsecurity
```
**Symbols:**

```
ffffffff816d3750-ffffffff816d37f0: smack_netlbl_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int smack_netlbl_add(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (0)
Location: security/smack/smack_lsm.c:2582
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_inode_setsecurity
```
**Symbols:**

```
ffffffff81711710-ffffffff817117e8: smack_netlbl_add (STB_LOCAL)
ffffffff821d0d4c-ffffffff821d0d61: smack_netlbl_add.cold (STB_LOCAL)
```
</details>
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
