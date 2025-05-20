# Function: <code>scan_revoke_records</code>

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
In fs/jbd2/recovery.c (ffffffff812ebeda)
Location: fs/jbd2/recovery.c:836
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
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
In fs/jbd2/recovery.c (ffffffff813199ec)
Location: fs/jbd2/recovery.c:815
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
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
In fs/jbd2/recovery.c (ffffffff8132f9dc)
Location: fs/jbd2/recovery.c:815
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
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
In fs/jbd2/recovery.c (ffffffff81344881)
Location: fs/jbd2/recovery.c:815
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
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
In fs/jbd2/recovery.c (ffffffff81368f21)
Location: fs/jbd2/recovery.c:815
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
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
In fs/jbd2/recovery.c (ffffffff813976bc)
Location: fs/jbd2/recovery.c:812
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
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
In fs/jbd2/recovery.c (ffffffff813b04f1)
Location: fs/jbd2/recovery.c:812
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
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
In fs/jbd2/recovery.c (ffffffff813da97e)
Location: fs/jbd2/recovery.c:812
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
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
In fs/jbd2/recovery.c (ffffffff813f49ce)
Location: fs/jbd2/recovery.c:812
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int scan_revoke_records(journal_t *journal, struct buffer_head *bh, tid_t sequence, struct recovery_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/recovery.c (ffffffff814419c0)
Location: fs/jbd2/recovery.c:812
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff814419c0-ffffffff81441bd3: scan_revoke_records (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int scan_revoke_records(journal_t *journal, struct buffer_head *bh, tid_t sequence, struct recovery_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/recovery.c (ffffffff8145dca0)
Location: fs/jbd2/recovery.c:896
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff8145dca0-ffffffff8145ddf5: scan_revoke_records (STB_LOCAL)
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
In fs/jbd2/recovery.c (ffffffff81463808)
Location: fs/jbd2/recovery.c:895
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
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
In fs/jbd2/recovery.c (ffffffff814b8d99)
Location: fs/jbd2/recovery.c:894
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
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
In fs/jbd2/recovery.c (ffffffff815429d4)
Location: fs/jbd2/recovery.c:894
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
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
In fs/jbd2/recovery.c (ffffffff815e16e0)
Location: fs/jbd2/recovery.c:899
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
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
In fs/jbd2/recovery.c (ffffffff81618fc9)
Location: fs/jbd2/recovery.c:911
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
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
In fs/jbd2/recovery.c (ffffffff81651eab)
Location: fs/jbd2/recovery.c:909
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
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
In fs/jbd2/recovery.c (ffff8000104d02b8)
Location: fs/jbd2/recovery.c:812
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
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
In fs/jbd2/recovery.c (c0692f34)
Location: fs/jbd2/recovery.c:812
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
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
In fs/jbd2/recovery.c (c0000000006093a4)
Location: fs/jbd2/recovery.c:812
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
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
In fs/jbd2/recovery.c (ffffffe000347614)
Location: fs/jbd2/recovery.c:812
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
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
In fs/jbd2/recovery.c (ffffffff813ecfae)
Location: fs/jbd2/recovery.c:812
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
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
In fs/jbd2/recovery.c (ffffffff813dda2e)
Location: fs/jbd2/recovery.c:812
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
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
In fs/jbd2/recovery.c (ffffffff813ea32e)
Location: fs/jbd2/recovery.c:812
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
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
In fs/jbd2/recovery.c (ffffffff813ffc81)
Location: fs/jbd2/recovery.c:812
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
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
</ul>
