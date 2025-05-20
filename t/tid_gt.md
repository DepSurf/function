# Function: <code>tid_gt</code>

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
In fs/jbd2/revoke.c (0)
Location: include/linux/jbd2.h:1393
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff812f2408)
Location: include/linux/jbd2.h:1393
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
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
In fs/jbd2/revoke.c (ffffffff8131b866)
Location: include/linux/jbd2.h:1408
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
```
```
In fs/jbd2/journal.c (ffffffff81320038)
Location: include/linux/jbd2.h:1408
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_update_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
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
In fs/jbd2/revoke.c (ffffffff81331856)
Location: include/linux/jbd2.h:1408
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
```
```
In fs/jbd2/journal.c (ffffffff81335ef8)
Location: include/linux/jbd2.h:1408
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_update_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
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
In fs/jbd2/revoke.c (ffffffff81346748)
Location: include/linux/jbd2.h:1410
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
```
```
In fs/jbd2/journal.c (ffffffff8134ac28)
Location: include/linux/jbd2.h:1410
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_update_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
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
In fs/jbd2/revoke.c (ffffffff8136add8)
Location: include/linux/jbd2.h:1516
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
```
```
In fs/jbd2/journal.c (ffffffff8136f278)
Location: include/linux/jbd2.h:1516
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_update_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
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
In fs/jbd2/revoke.c (ffffffff81399516)
Location: include/linux/jbd2.h:1516
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
```
```
In fs/jbd2/journal.c (ffffffff8139d838)
Location: include/linux/jbd2.h:1516
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_update_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
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
In fs/jbd2/revoke.c (ffffffff813b2286)
Location: include/linux/jbd2.h:1517
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
```
```
In fs/jbd2/journal.c (ffffffff813b65a8)
Location: include/linux/jbd2.h:1517
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_update_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
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
In fs/jbd2/revoke.c (ffffffff813dc8f6)
Location: include/linux/jbd2.h:1537
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
```
```
In fs/jbd2/journal.c (ffffffff813e0d09)
Location: include/linux/jbd2.h:1537
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_update_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
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
In fs/jbd2/revoke.c (ffffffff813f6936)
Location: include/linux/jbd2.h:1535
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
```
```
In fs/jbd2/journal.c (ffffffff813fad59)
Location: include/linux/jbd2.h:1535
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_update_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
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
In fs/jbd2/revoke.c (ffffffff81443da6)
Location: include/linux/jbd2.h:1539
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
```
```
In fs/jbd2/journal.c (ffffffff814484f9)
Location: include/linux/jbd2.h:1539
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_update_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
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
In fs/jbd2/revoke.c (ffffffff8145fe86)
Location: include/linux/jbd2.h:1667
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
```
```
In fs/jbd2/journal.c (ffffffff81465029)
Location: include/linux/jbd2.h:1667
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_update_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
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
In fs/jbd2/revoke.c (ffffffff81465656)
Location: include/linux/jbd2.h:1676
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
```
```
In fs/jbd2/journal.c (ffffffff8146a7b9)
Location: include/linux/jbd2.h:1676
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_update_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
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
In fs/jbd2/revoke.c (ffffffff814bafd6)
Location: include/linux/jbd2.h:1715
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
```
```
In fs/jbd2/journal.c (ffffffff814c0f39)
Location: include/linux/jbd2.h:1715
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_update_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
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
In fs/jbd2/revoke.c (ffffffff81544ec6)
Location: include/linux/jbd2.h:1709
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
```
```
In fs/jbd2/journal.c (ffffffff8154b808)
Location: include/linux/jbd2.h:1709
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_update_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
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
In fs/jbd2/revoke.c (ffffffff815e4026)
Location: include/linux/jbd2.h:1707
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
```
```
In fs/jbd2/journal.c (ffffffff815eb508)
Location: include/linux/jbd2.h:1707
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_update_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
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
In fs/jbd2/revoke.c (ffffffff8161b7f6)
Location: include/linux/jbd2.h:1708
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
```
```
In fs/jbd2/journal.c (ffffffff81622f78)
Location: include/linux/jbd2.h:1708
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_update_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
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
In fs/jbd2/revoke.c (ffffffff81654716)
Location: include/linux/jbd2.h:1721
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
```
```
In fs/jbd2/journal.c (ffffffff8165bff8)
Location: include/linux/jbd2.h:1721
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_update_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
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
In fs/jbd2/revoke.c (ffff8000104d2b84)
Location: include/linux/jbd2.h:1535
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
```
```
In fs/jbd2/journal.c (ffff8000104d8250)
Location: include/linux/jbd2.h:1535
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_update_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
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
In fs/jbd2/revoke.c (c06951d4)
Location: include/linux/jbd2.h:1535
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
```
```
In fs/jbd2/journal.c (c069a0b4)
Location: include/linux/jbd2.h:1535
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_update_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
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
In fs/jbd2/revoke.c (c00000000060c4a0)
Location: include/linux/jbd2.h:1535
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
```
```
In fs/jbd2/journal.c (c000000000612f88)
Location: include/linux/jbd2.h:1535
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_update_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
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
In fs/jbd2/revoke.c (ffffffe000349ac6)
Location: include/linux/jbd2.h:1535
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
```
```
In fs/jbd2/journal.c (ffffffe00034dd48)
Location: include/linux/jbd2.h:1535
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_update_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
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
In fs/jbd2/revoke.c (ffffffff813eef16)
Location: include/linux/jbd2.h:1535
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
```
```
In fs/jbd2/journal.c (ffffffff813f3339)
Location: include/linux/jbd2.h:1535
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_update_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
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
In fs/jbd2/revoke.c (ffffffff813df996)
Location: include/linux/jbd2.h:1535
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
```
```
In fs/jbd2/journal.c (ffffffff813e3db9)
Location: include/linux/jbd2.h:1535
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_update_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
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
In fs/jbd2/revoke.c (ffffffff813ec296)
Location: include/linux/jbd2.h:1535
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
```
```
In fs/jbd2/journal.c (ffffffff813f06b9)
Location: include/linux/jbd2.h:1535
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_update_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
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
In fs/jbd2/revoke.c (ffffffff81401c36)
Location: include/linux/jbd2.h:1535
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_test_revoke
  - fs/jbd2/revoke.c:jbd2_journal_set_revoke
```
```
In fs/jbd2/journal.c (ffffffff81406129)
Location: include/linux/jbd2.h:1535
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_update_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
```
</details>
</li>
</ul>

## Differences
