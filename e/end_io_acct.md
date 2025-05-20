# Function: <code>end_io_acct</code>

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
In drivers/md/dm.c (ffffffff816a0a38)
Location: drivers/md/dm.c:693
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
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
In drivers/md/dm.c (ffffffff81701d80)
Location: drivers/md/dm.c:526
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
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
In drivers/md/dm.c (ffffffff81733bcc)
Location: drivers/md/dm.c:526
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
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
In drivers/md/dm.c (ffffffff8174cd12)
Location: drivers/md/dm.c:524
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
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
In drivers/md/dm.c (ffffffff817beee2)
Location: drivers/md/dm.c:531
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
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
In drivers/md/dm.c (ffffffff818075a3)
Location: drivers/md/dm.c:623
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
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
In drivers/md/dm.c (ffffffff818335ae)
Location: drivers/md/dm.c:687
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
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
In drivers/md/dm.c (ffffffff818754de)
Location: drivers/md/dm.c:667
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
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
In drivers/md/dm.c (ffffffff818a728e)
Location: drivers/md/dm.c:667
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void end_io_acct(struct dm_io *io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81976fc0)
Location: drivers/md/dm.c:681
Inline: False
Direct callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dec_pending
```
**Symbols:**

```
ffffffff81976fc0-ffffffff8197708f: end_io_acct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void end_io_acct(struct dm_io *io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8197bd60)
Location: drivers/md/dm.c:613
Inline: False
Direct callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dec_pending
```
**Symbols:**

```
ffffffff8197bd60-ffffffff8197be2f: end_io_acct (STB_LOCAL)
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
In drivers/md/dm.c (ffffffff8196088a)
Location: drivers/md/dm.c:618
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
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
In drivers/md/dm.c (ffffffff81a0a291)
Location: drivers/md/dm.c:499
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_io_dec_pending
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:667
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
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
In drivers/md/dm.c (c0bdccbc)
Location: drivers/md/dm.c:667
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
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
In drivers/md/dm.c (c000000000beac74)
Location: drivers/md/dm.c:667
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
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
In drivers/md/dm.c (ffffffe0006ed808)
Location: drivers/md/dm.c:667
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
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
In drivers/md/dm.c (ffffffff8184d10e)
Location: drivers/md/dm.c:667
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
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
In drivers/md/dm.c (ffffffff8181472e)
Location: drivers/md/dm.c:667
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
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
In drivers/md/dm.c (ffffffff8189c73e)
Location: drivers/md/dm.c:667
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
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
In drivers/md/dm.c (ffffffff818b897e)
Location: drivers/md/dm.c:667
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
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
