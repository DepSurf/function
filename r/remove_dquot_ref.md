# Function: <code>remove_dquot_ref</code>

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
In fs/quota/dquot.c (ffffffff81273199)
Location: fs/quota/dquot.c:1031
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
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
In fs/quota/dquot.c (ffffffff8129fc16)
Location: fs/quota/dquot.c:1040
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
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
In fs/quota/dquot.c (ffffffff812b5142)
Location: fs/quota/dquot.c:1037
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
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
In fs/quota/dquot.c (ffffffff812c1964)
Location: fs/quota/dquot.c:1038
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
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
In fs/quota/dquot.c (ffffffff812e5764)
Location: fs/quota/dquot.c:1051
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
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
In fs/quota/dquot.c (ffffffff81312bdd)
Location: fs/quota/dquot.c:1048
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
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
In fs/quota/dquot.c (ffffffff81329b6d)
Location: fs/quota/dquot.c:1048
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
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
In fs/quota/dquot.c (ffffffff81351750)
Location: fs/quota/dquot.c:1054
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
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
In fs/quota/dquot.c (ffffffff81369ad0)
Location: fs/quota/dquot.c:1056
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void remove_dquot_ref(struct super_block *sb, int type, struct list_head *tofree_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813b0d50)
Location: fs/quota/dquot.c:1054
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_disable
```
**Symbols:**

```
ffffffff813b0d50-ffffffff813b0e71: remove_dquot_ref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void remove_dquot_ref(struct super_block *sb, int type, struct list_head *tofree_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813c2350)
Location: fs/quota/dquot.c:1055
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_disable
```
**Symbols:**

```
ffffffff813c2350-ffffffff813c2471: remove_dquot_ref (STB_LOCAL)
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
In fs/quota/dquot.c (ffffffff813c9f56)
Location: fs/quota/dquot.c:1053
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
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
In fs/quota/dquot.c (ffffffff8141aa03)
Location: fs/quota/dquot.c:1058
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
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
In fs/quota/dquot.c (ffffffff81490bef)
Location: fs/quota/dquot.c:1068
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
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
In fs/quota/dquot.c (ffffffff8152479f)
Location: fs/quota/dquot.c:1068
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
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
In fs/quota/dquot.c (ffffffff8155cbc5)
Location: fs/quota/dquot.c:1126
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
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
In fs/quota/dquot.c (ffffffff81593365)
Location: fs/quota/dquot.c:1081
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
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
In fs/quota/dquot.c (ffff800010431db0)
Location: fs/quota/dquot.c:1056
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
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
In fs/quota/dquot.c (c05f9db0)
Location: fs/quota/dquot.c:1056
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
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
In fs/quota/dquot.c (c000000000542f84)
Location: fs/quota/dquot.c:1056
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
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
In fs/quota/dquot.c (ffffffe0002ce0fe)
Location: fs/quota/dquot.c:1056
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
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
In fs/quota/dquot.c (ffffffff813620b0)
Location: fs/quota/dquot.c:1056
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
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
In fs/quota/dquot.c (ffffffff81352d50)
Location: fs/quota/dquot.c:1056
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
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
In fs/quota/dquot.c (ffffffff8135fb80)
Location: fs/quota/dquot.c:1056
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
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
In fs/quota/dquot.c (ffffffff8137264b)
Location: fs/quota/dquot.c:1056
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
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
