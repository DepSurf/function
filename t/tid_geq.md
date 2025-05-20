# Function: <code>tid_geq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff812e6b5e)
Location: include/linux/jbd2.h:1399
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/transaction.c:jbd2__journal_restart
```
```
In fs/jbd2/recovery.c (0)
Location: include/linux/jbd2.h:1399
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/jbd2.h:1399
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81315354)
Location: include/linux/jbd2.h:1414
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/recovery.c (0)
Location: include/linux/jbd2.h:1414
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff8131eed2)
Location: include/linux/jbd2.h:1414
Inline: True
Inline callers:
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8132b354)
Location: include/linux/jbd2.h:1414
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/recovery.c (0)
Location: include/linux/jbd2.h:1414
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff81334f52)
Location: include/linux/jbd2.h:1414
Inline: True
Inline callers:
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81340578)
Location: include/linux/jbd2.h:1416
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/recovery.c (0)
Location: include/linux/jbd2.h:1416
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff81349cc6)
Location: include/linux/jbd2.h:1416
Inline: True
Inline callers:
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81364b88)
Location: include/linux/jbd2.h:1522
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/recovery.c (0)
Location: include/linux/jbd2.h:1522
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff8136e316)
Location: include/linux/jbd2.h:1522
Inline: True
Inline callers:
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813932f8)
Location: include/linux/jbd2.h:1522
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/recovery.c (ffffffff8139737d)
Location: include/linux/jbd2.h:1522
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff8139c9ac)
Location: include/linux/jbd2.h:1522
Inline: True
Inline callers:
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_log_start_commit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813ac018)
Location: include/linux/jbd2.h:1523
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/recovery.c (ffffffff813b00ad)
Location: include/linux/jbd2.h:1523
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff813b571c)
Location: include/linux/jbd2.h:1523
Inline: True
Inline callers:
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_log_start_commit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813d629c)
Location: include/linux/jbd2.h:1543
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/recovery.c (ffffffff813da64b)
Location: include/linux/jbd2.h:1543
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff813dfdf2)
Location: include/linux/jbd2.h:1543
Inline: True
Inline callers:
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_log_start_commit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813f02cc)
Location: include/linux/jbd2.h:1541
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/recovery.c (ffffffff813f469b)
Location: include/linux/jbd2.h:1541
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff813f9e42)
Location: include/linux/jbd2.h:1541
Inline: True
Inline callers:
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_log_start_commit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8143d670)
Location: include/linux/jbd2.h:1545
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/recovery.c (ffffffff81441c59)
Location: include/linux/jbd2.h:1545
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff81447dec)
Location: include/linux/jbd2.h:1545
Inline: True
Inline callers:
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_log_start_commit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff814599e1)
Location: include/linux/jbd2.h:1673
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/recovery.c (ffffffff8145de87)
Location: include/linux/jbd2.h:1673
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff8146477c)
Location: include/linux/jbd2.h:1673
Inline: True
Inline callers:
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_log_start_commit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8145f2a1)
Location: include/linux/jbd2.h:1682
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/recovery.c (ffffffff81463542)
Location: include/linux/jbd2.h:1682
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff81469f0c)
Location: include/linux/jbd2.h:1682
Inline: True
Inline callers:
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_log_start_commit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff814b4751)
Location: include/linux/jbd2.h:1721
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/recovery.c (ffffffff814b8ac5)
Location: include/linux/jbd2.h:1721
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff814c028f)
Location: include/linux/jbd2.h:1721
Inline: True
Inline callers:
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_log_start_commit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8153e055)
Location: include/linux/jbd2.h:1715
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/recovery.c (ffffffff81542693)
Location: include/linux/jbd2.h:1715
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff8154aa8b)
Location: include/linux/jbd2.h:1715
Inline: True
Inline callers:
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_log_start_commit
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff815dc925)
Location: include/linux/jbd2.h:1713
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/recovery.c (ffffffff815e13c5)
Location: include/linux/jbd2.h:1713
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff815e92fb)
Location: include/linux/jbd2.h:1713
Inline: True
Inline callers:
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_log_start_commit
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff816143c5)
Location: include/linux/jbd2.h:1714
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/recovery.c (ffffffff81618cc2)
Location: include/linux/jbd2.h:1714
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff81620b9b)
Location: include/linux/jbd2.h:1714
Inline: True
Inline callers:
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_log_start_commit
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8164d1b5)
Location: include/linux/jbd2.h:1727
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/recovery.c (ffffffff81651c3c)
Location: include/linux/jbd2.h:1727
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff816597d8)
Location: include/linux/jbd2.h:1727
Inline: True
Inline callers:
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_log_start_commit
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffff8000104c9b98)
Location: include/linux/jbd2.h:1541
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/recovery.c (ffff8000104cfff8)
Location: include/linux/jbd2.h:1541
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffff8000104d6a44)
Location: include/linux/jbd2.h:1541
Inline: True
Inline callers:
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_log_start_commit
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (c068d6ec)
Location: include/linux/jbd2.h:1541
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/recovery.c (c0692b04)
Location: include/linux/jbd2.h:1541
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (c0698cf8)
Location: include/linux/jbd2.h:1541
Inline: True
Inline callers:
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_log_start_commit
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (c000000000602384)
Location: include/linux/jbd2.h:1541
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/recovery.c (c000000000609044)
Location: include/linux/jbd2.h:1541
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (c0000000006115b4)
Location: include/linux/jbd2.h:1541
Inline: True
Inline callers:
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_log_start_commit
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffe0003430c2)
Location: include/linux/jbd2.h:1541
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/recovery.c (ffffffe00034763c)
Location: include/linux/jbd2.h:1541
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffe00034cafc)
Location: include/linux/jbd2.h:1541
Inline: True
Inline callers:
  - fs/jbd2/journal.c:__jbd2_log_start_commit
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813e88ac)
Location: include/linux/jbd2.h:1541
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/recovery.c (ffffffff813ecc7b)
Location: include/linux/jbd2.h:1541
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff813f2422)
Location: include/linux/jbd2.h:1541
Inline: True
Inline callers:
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_log_start_commit
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813d932c)
Location: include/linux/jbd2.h:1541
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/recovery.c (ffffffff813dd6fb)
Location: include/linux/jbd2.h:1541
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff813e2ea2)
Location: include/linux/jbd2.h:1541
Inline: True
Inline callers:
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_log_start_commit
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813e5c2c)
Location: include/linux/jbd2.h:1541
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/recovery.c (ffffffff813e9ffb)
Location: include/linux/jbd2.h:1541
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff813ef7a2)
Location: include/linux/jbd2.h:1541
Inline: True
Inline callers:
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_log_start_commit
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813fad08)
Location: include/linux/jbd2.h:1541
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/recovery.c (ffffffff813ff946)
Location: include/linux/jbd2.h:1541
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff81405172)
Location: include/linux/jbd2.h:1541
Inline: True
Inline callers:
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_log_start_commit
```
</details>
</li>
</ul>

## Differences
