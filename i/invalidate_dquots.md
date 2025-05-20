# Function: <code>invalidate_dquots</code>

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
In fs/quota/dquot.c (ffffffff812731bb)
Location: fs/quota/dquot.c:513
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
In fs/quota/dquot.c (ffffffff8129fa53)
Location: fs/quota/dquot.c:520
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
In fs/quota/dquot.c (ffffffff812b4fb0)
Location: fs/quota/dquot.c:519
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
In fs/quota/dquot.c (ffffffff812c18d0)
Location: fs/quota/dquot.c:520
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
In fs/quota/dquot.c (ffffffff812e58aa)
Location: fs/quota/dquot.c:530
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
In fs/quota/dquot.c (0)
Location: fs/quota/dquot.c:530
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
In fs/quota/dquot.c (0)
Location: fs/quota/dquot.c:530
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
In fs/quota/dquot.c (0)
Location: fs/quota/dquot.c:536
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
In fs/quota/dquot.c (0)
Location: fs/quota/dquot.c:536
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
void invalidate_dquots(struct super_block *sb, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813b12d0)
Location: fs/quota/dquot.c:536
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_disable
```
**Symbols:**

```
ffffffff813b12d0-ffffffff813b14ee: invalidate_dquots (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void invalidate_dquots(struct super_block *sb, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813c28d0)
Location: fs/quota/dquot.c:537
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_disable
```
**Symbols:**

```
ffffffff813c28d0-ffffffff813c2aee: invalidate_dquots (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void invalidate_dquots(struct super_block *sb, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813c94a0)
Location: fs/quota/dquot.c:535
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_disable
```
**Symbols:**

```
ffffffff813c94a0-ffffffff813c96be: invalidate_dquots (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void invalidate_dquots(struct super_block *sb, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81419d20)
Location: fs/quota/dquot.c:535
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_disable
```
**Symbols:**

```
ffffffff81419d20-ffffffff81419f3e: invalidate_dquots (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void invalidate_dquots(struct super_block *sb, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81490750)
Location: fs/quota/dquot.c:545
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_disable
```
**Symbols:**

```
ffffffff81490750-ffffffff814909a2: invalidate_dquots (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void invalidate_dquots(struct super_block *sb, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff815242f0)
Location: fs/quota/dquot.c:545
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_disable
```
**Symbols:**

```
ffffffff815242f0-ffffffff81524542: invalidate_dquots (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void invalidate_dquots(struct super_block *sb, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8155c710)
Location: fs/quota/dquot.c:569
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_disable
```
**Symbols:**

```
ffffffff8155c710-ffffffff8155c96d: invalidate_dquots (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void invalidate_dquots(struct super_block *sb, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81592ed0)
Location: fs/quota/dquot.c:571
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_disable
```
**Symbols:**

```
ffffffff81592ed0-ffffffff8159313e: invalidate_dquots (STB_LOCAL)
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
In fs/quota/dquot.c (0)
Location: fs/quota/dquot.c:536
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
In fs/quota/dquot.c (0)
Location: fs/quota/dquot.c:536
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
In fs/quota/dquot.c (0)
Location: fs/quota/dquot.c:536
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
In fs/quota/dquot.c (ffffffe0002ce1c6)
Location: fs/quota/dquot.c:536
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
In fs/quota/dquot.c (0)
Location: fs/quota/dquot.c:536
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
In fs/quota/dquot.c (0)
Location: fs/quota/dquot.c:536
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
In fs/quota/dquot.c (0)
Location: fs/quota/dquot.c:536
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
In fs/quota/dquot.c (0)
Location: fs/quota/dquot.c:536
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
