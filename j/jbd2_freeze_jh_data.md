# Function: <code>jbd2_freeze_jh_data</code>

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
In fs/jbd2/transaction.c (ffffffff812e8743)
Location: fs/jbd2/transaction.c:777
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
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
In fs/jbd2/transaction.c (ffffffff81316359)
Location: fs/jbd2/transaction.c:774
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
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
In fs/jbd2/transaction.c (ffffffff8132c349)
Location: fs/jbd2/transaction.c:776
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
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
In fs/jbd2/transaction.c (ffffffff813415ee)
Location: fs/jbd2/transaction.c:789
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
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
In fs/jbd2/transaction.c (ffffffff81365c19)
Location: fs/jbd2/transaction.c:792
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
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
In fs/jbd2/transaction.c (ffffffff81394393)
Location: fs/jbd2/transaction.c:788
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
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
In fs/jbd2/transaction.c (ffffffff813ad0e3)
Location: fs/jbd2/transaction.c:821
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
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
In fs/jbd2/transaction.c (ffffffff813d739b)
Location: fs/jbd2/transaction.c:821
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
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
In fs/jbd2/transaction.c (ffffffff813f13cb)
Location: fs/jbd2/transaction.c:824
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void jbd2_freeze_jh_data(struct journal_head *jh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:903
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
**Symbols:**

```
ffffffff8143c8f0-ffffffff8143c997: jbd2_freeze_jh_data (STB_LOCAL)
ffffffff8143f795-ffffffff8143f7c0: jbd2_freeze_jh_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void jbd2_freeze_jh_data(struct journal_head *jh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:905
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
**Symbols:**

```
ffffffff81458c70-ffffffff81458d17: jbd2_freeze_jh_data (STB_LOCAL)
ffffffff81becb39-ffffffff81becb64: jbd2_freeze_jh_data.cold (STB_LOCAL)
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
In fs/jbd2/transaction.c (ffffffff814603ab)
Location: fs/jbd2/transaction.c:910
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
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
In fs/jbd2/transaction.c (ffffffff814b582e)
Location: fs/jbd2/transaction.c:927
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:936
Inline: True
Direct callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
**Symbols:**

```
ffffffff8153d430-ffffffff8153d501: jbd2_freeze_jh_data.constprop.0 (STB_LOCAL)
ffffffff81e814a6-ffffffff81e814d1: jbd2_freeze_jh_data.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void jbd2_freeze_jh_data(struct journal_head *jh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff815dbc60)
Location: fs/jbd2/transaction.c:936
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
**Symbols:**

```
ffffffff815dbc60-ffffffff815dbd5b: jbd2_freeze_jh_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void jbd2_freeze_jh_data(struct journal_head *jh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81613720)
Location: fs/jbd2/transaction.c:936
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
**Symbols:**

```
ffffffff81613720-ffffffff81613819: jbd2_freeze_jh_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void jbd2_freeze_jh_data(struct journal_head *jh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:936
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
**Symbols:**

```
ffffffff8164c520-ffffffff8164c618: jbd2_freeze_jh_data (STB_LOCAL)
ffffffff821ce1c4-ffffffff821ce1de: jbd2_freeze_jh_data.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffff8000104cb390)
Location: fs/jbd2/transaction.c:824
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (c068ed7c)
Location: fs/jbd2/transaction.c:824
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (c00000000060443c)
Location: fs/jbd2/transaction.c:824
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
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
In fs/jbd2/transaction.c (ffffffe0003441b8)
Location: fs/jbd2/transaction.c:824
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
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
In fs/jbd2/transaction.c (ffffffff813e99ab)
Location: fs/jbd2/transaction.c:824
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
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
In fs/jbd2/transaction.c (ffffffff813da42b)
Location: fs/jbd2/transaction.c:824
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
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
In fs/jbd2/transaction.c (ffffffff813e6d2b)
Location: fs/jbd2/transaction.c:824
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
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
In fs/jbd2/transaction.c (ffffffff813fc30b)
Location: fs/jbd2/transaction.c:824
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
