# Function: <code>put_multi_transaction</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void put_multi_transaction(struct multi_transaction *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813d85d0)
Location: security/apparmor/apparmorfs.c:835
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:multi_transaction_release
  - security/apparmor/apparmorfs.c:multi_transaction_read
```
**Symbols:**

```
ffffffff813d85d0-ffffffff813d85ee: put_multi_transaction (STB_LOCAL)
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
In security/apparmor/apparmorfs.c (ffffffff81401dc2)
Location: security/apparmor/apparmorfs.c:836
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:multi_transaction_release
  - security/apparmor/apparmorfs.c:multi_transaction_read
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
In security/apparmor/apparmorfs.c (ffffffff81432d1e)
Location: security/apparmor/apparmorfs.c:833
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:multi_transaction_release
  - security/apparmor/apparmorfs.c:multi_transaction_read
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
In security/apparmor/apparmorfs.c (ffffffff8144f9ce)
Location: security/apparmor/apparmorfs.c:831
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:multi_transaction_release
  - security/apparmor/apparmorfs.c:multi_transaction_read
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
In security/apparmor/apparmorfs.c (ffffffff8147d6b0)
Location: security/apparmor/apparmorfs.c:836
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:multi_transaction_release
  - security/apparmor/apparmorfs.c:multi_transaction_read
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
In security/apparmor/apparmorfs.c (ffffffff81497380)
Location: security/apparmor/apparmorfs.c:804
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:multi_transaction_release
  - security/apparmor/apparmorfs.c:multi_transaction_read
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
In security/apparmor/apparmorfs.c (ffffffff814ef010)
Location: security/apparmor/apparmorfs.c:835
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:multi_transaction_release
  - security/apparmor/apparmorfs.c:multi_transaction_read
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
In security/apparmor/apparmorfs.c (ffffffff8150c490)
Location: security/apparmor/apparmorfs.c:835
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:multi_transaction_release
  - security/apparmor/apparmorfs.c:multi_transaction_read
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
In security/apparmor/apparmorfs.c (ffffffff81512e10)
Location: security/apparmor/apparmorfs.c:835
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:multi_transaction_release
  - security/apparmor/apparmorfs.c:multi_transaction_read
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
In security/apparmor/apparmorfs.c (ffffffff81570a10)
Location: security/apparmor/apparmorfs.c:835
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:multi_transaction_release
  - security/apparmor/apparmorfs.c:multi_transaction_read
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
In security/apparmor/apparmorfs.c (ffffffff8160d4a5)
Location: security/apparmor/apparmorfs.c:837
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:multi_transaction_release
  - security/apparmor/apparmorfs.c:multi_transaction_release
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:multi_transaction_read
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
In security/apparmor/apparmorfs.c (ffffffff816bf415)
Location: security/apparmor/apparmorfs.c:1004
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:multi_transaction_release
  - security/apparmor/apparmorfs.c:multi_transaction_release
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:multi_transaction_read
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
In security/apparmor/apparmorfs.c (ffffffff816f7f25)
Location: security/apparmor/apparmorfs.c:1049
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:multi_transaction_release
  - security/apparmor/apparmorfs.c:multi_transaction_release
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:multi_transaction_read
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
In security/apparmor/apparmorfs.c (ffffffff81734c95)
Location: security/apparmor/apparmorfs.c:1050
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:multi_transaction_release
  - security/apparmor/apparmorfs.c:multi_transaction_release
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:multi_transaction_read
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (ffff80001058d100)
Location: security/apparmor/apparmorfs.c:804
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:multi_transaction_release
  - security/apparmor/apparmorfs.c:multi_transaction_read
Direct callers:
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:multi_transaction_release
  - security/apparmor/apparmorfs.c:multi_transaction_read
```
**Symbols:**

```
ffff800010589f78-ffff800010589fb8: put_multi_transaction.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (c073ddbc)
Location: security/apparmor/apparmorfs.c:804
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:multi_transaction_release
  - security/apparmor/apparmorfs.c:multi_transaction_read
Direct callers:
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:multi_transaction_release
  - security/apparmor/apparmorfs.c:multi_transaction_read
```
**Symbols:**

```
c073b090-c073b0c4: put_multi_transaction.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void put_multi_transaction(struct multi_transaction *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (c0000000006fa370)
Location: security/apparmor/apparmorfs.c:804
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:multi_transaction_release
  - security/apparmor/apparmorfs.c:multi_transaction_read
```
**Symbols:**

```
c0000000006fa370-c0000000006fa3d4: put_multi_transaction (STB_LOCAL)
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
In security/apparmor/apparmorfs.c (ffffffe0003db340)
Location: security/apparmor/apparmorfs.c:804
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:multi_transaction_release
  - security/apparmor/apparmorfs.c:multi_transaction_read
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
In security/apparmor/apparmorfs.c (ffffffff8148f960)
Location: security/apparmor/apparmorfs.c:804
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:multi_transaction_release
  - security/apparmor/apparmorfs.c:multi_transaction_read
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
In security/apparmor/apparmorfs.c (ffffffff81480380)
Location: security/apparmor/apparmorfs.c:804
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:multi_transaction_release
  - security/apparmor/apparmorfs.c:multi_transaction_read
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
In security/apparmor/apparmorfs.c (ffffffff8148ba00)
Location: security/apparmor/apparmorfs.c:804
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:multi_transaction_release
  - security/apparmor/apparmorfs.c:multi_transaction_read
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
In security/apparmor/apparmorfs.c (ffffffff814a37e0)
Location: security/apparmor/apparmorfs.c:804
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:multi_transaction_release
  - security/apparmor/apparmorfs.c:multi_transaction_read
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
