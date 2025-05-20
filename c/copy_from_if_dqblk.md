# Function: <code>copy_from_if_dqblk</code>

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
In fs/quota/quota.c (ffffffff812757d0)
Location: fs/quota/quota.c:225
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setquota
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
In fs/quota/quota.c (ffffffff812a1d52)
Location: fs/quota/quota.c:253
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setquota
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
In fs/quota/quota.c (ffffffff812b7722)
Location: fs/quota/quota.c:249
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setquota
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
In fs/quota/quota.c (ffffffff812c498a)
Location: fs/quota/quota.c:249
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setquota
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
In fs/quota/quota.c (ffffffff812e882a)
Location: fs/quota/quota.c:250
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setquota
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
In fs/quota/quota.c (ffffffff8131590a)
Location: fs/quota/quota.c:251
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setquota
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
In fs/quota/quota.c (ffffffff8132c32a)
Location: fs/quota/quota.c:249
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setquota
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
In fs/quota/quota.c (ffffffff81353fa5)
Location: fs/quota/quota.c:249
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setquota
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
In fs/quota/quota.c (ffffffff8136c315)
Location: fs/quota/quota.c:249
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setquota
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void copy_from_if_dqblk(struct qc_dqblk *dst, struct if_dqblk *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff813b35a0)
Location: fs/quota/quota.c:247
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_setquota
```
**Symbols:**

```
ffffffff813b35a0-ffffffff813b3640: copy_from_if_dqblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void copy_from_if_dqblk(struct qc_dqblk *dst, struct if_dqblk *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff813c4b50)
Location: fs/quota/quota.c:259
Inline: False
Direct callers:
  - fs/quota/quota.c:quota_setquota
```
**Symbols:**

```
ffffffff813c4b50-ffffffff813c4bf0: copy_from_if_dqblk (STB_LOCAL)
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
In fs/quota/quota.c (ffffffff813cce6b)
Location: fs/quota/quota.c:260
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setquota
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
In fs/quota/quota.c (ffffffff8141e128)
Location: fs/quota/quota.c:260
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setquota
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
In fs/quota/quota.c (ffffffff81495e05)
Location: fs/quota/quota.c:261
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setquota
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
In fs/quota/quota.c (ffffffff81529d55)
Location: fs/quota/quota.c:261
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setquota
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
In fs/quota/quota.c (ffffffff81562104)
Location: fs/quota/quota.c:261
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setquota
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
In fs/quota/quota.c (ffffffff815987f4)
Location: fs/quota/quota.c:261
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setquota
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
In fs/quota/quota.c (ffff800010436134)
Location: fs/quota/quota.c:249
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setquota
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
In fs/quota/quota.c (c05fdec0)
Location: fs/quota/quota.c:249
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setquota
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
In fs/quota/quota.c (c00000000054822c)
Location: fs/quota/quota.c:249
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setquota
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
In fs/quota/quota.c (ffffffe0002d088e)
Location: fs/quota/quota.c:249
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setquota
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
In fs/quota/quota.c (ffffffff813648f5)
Location: fs/quota/quota.c:249
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setquota
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
In fs/quota/quota.c (ffffffff81355595)
Location: fs/quota/quota.c:249
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setquota
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
In fs/quota/quota.c (ffffffff813623c5)
Location: fs/quota/quota.c:249
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setquota
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
In fs/quota/quota.c (ffffffff81375a75)
Location: fs/quota/quota.c:249
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setquota
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
