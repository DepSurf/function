# Function: <code>make_kqid</code>

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
In fs/quota/quota.c (ffffffff8127522c)
Location: include/linux/quota.h:97
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_getquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getxquota
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
In fs/quota/quota.c (ffffffff812a21f3)
Location: include/linux/quota.h:97
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
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
In fs/quota/quota.c (ffffffff812b7bc3)
Location: include/linux/quota.h:97
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/quota.c (ffffffff812c4f03)
Location: include/linux/quota.h:97
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
Direct callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
```
**Symbols:**

```
ffffffff812c586c-ffffffff812c5872: make_kqid.part.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/quota.c (ffffffff812e8da3)
Location: include/linux/quota.h:97
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
Direct callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
```
**Symbols:**

```
ffffffff812e971d-ffffffff812e9723: make_kqid.part.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/quota.c (ffffffff813155c2)
Location: include/linux/quota.h:97
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
Direct callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
```
**Symbols:**

```
ffffffff81314e70-ffffffff81314e76: make_kqid.part.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/quota.c (ffffffff8132c8b2)
Location: include/linux/quota.h:97
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
Direct callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
```
**Symbols:**

```
ffffffff8132be00-ffffffff8132be06: make_kqid.part.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/quota.c (ffffffff81354546)
Location: include/linux/quota.h:97
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
Direct callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
```
**Symbols:**

```
ffffffff81353a70-ffffffff81353a72: make_kqid.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/quota.c (ffffffff8136c8b6)
Location: include/linux/quota.h:97
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
Direct callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
```
**Symbols:**

```
ffffffff8136bde0-ffffffff8136bde2: make_kqid.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/quota.c (ffffffff813b4754)
Location: include/linux/quota.h:97
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
Direct callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
```
**Symbols:**

```
ffffffff813b3c00-ffffffff813b3c02: make_kqid.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/quota.c (ffffffff813c5e84)
Location: include/linux/quota.h:97
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
Direct callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
```
**Symbols:**

```
ffffffff813c55a0-ffffffff813c55a2: make_kqid.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/quota.c (ffffffff813ccad4)
Location: include/linux/quota.h:97
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
Direct callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
```
**Symbols:**

```
ffffffff813cbfa0-ffffffff813cbfa2: make_kqid.part.0 (STB_LOCAL)
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
In fs/quota/quota.c (ffffffff8141dd94)
Location: include/linux/quota.h:97
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
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
In fs/quota/quota.c (ffffffff81495798)
Location: include/linux/quota.h:97
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
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
In fs/quota/quota.c (ffffffff815296b8)
Location: include/linux/quota.h:97
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
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
In fs/quota/quota.c (ffffffff81561d28)
Location: include/linux/quota.h:97
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
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
In mm/shmem_quota.c (ffffffff81408f9d)
Location: include/linux/quota.h:97
Inline: True
Inline callers:
  - mm/shmem_quota.c:shmem_get_next_id
```
```
In fs/quota/quota.c (ffffffff81598418)
Location: include/linux/quota.h:97
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
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
In fs/quota/quota.c (ffff800010436760)
Location: include/linux/quota.h:97
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
Direct callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
```
**Symbols:**

```
ffff800010435788-ffff80001043578c: make_kqid.part.0 (STB_LOCAL)
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
In fs/quota/quota.c (c05fdae0)
Location: include/linux/quota.h:97
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
Direct callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
```
**Symbols:**

```
c05fd41c-c05fd42c: make_kqid.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/quota.c (c000000000548964)
Location: include/linux/quota.h:97
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
Direct callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
```
**Symbols:**

```
c000000000547be0-c000000000547be4: make_kqid.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/quota.c (ffffffe0002d0d96)
Location: include/linux/quota.h:97
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
Direct callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
```
**Symbols:**

```
ffffffe0002d0408-ffffffe0002d0410: make_kqid.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/quota.c (ffffffff81364e96)
Location: include/linux/quota.h:97
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
Direct callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
```
**Symbols:**

```
ffffffff813643c0-ffffffff813643c2: make_kqid.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/quota.c (ffffffff81355b36)
Location: include/linux/quota.h:97
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
Direct callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
```
**Symbols:**

```
ffffffff81355060-ffffffff81355062: make_kqid.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/quota.c (ffffffff81362966)
Location: include/linux/quota.h:97
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
Direct callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
```
**Symbols:**

```
ffffffff81361e90-ffffffff81361e92: make_kqid.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/quota.c (ffffffff81376016)
Location: include/linux/quota.h:97
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
Direct callers:
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
```
**Symbols:**

```
ffffffff81375540-ffffffff81375542: make_kqid.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
