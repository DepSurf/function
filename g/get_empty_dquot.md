# Function: <code>get_empty_dquot</code>

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
In fs/quota/dquot.c (ffffffff81271c23)
Location: fs/quota/dquot.c:803
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
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
In fs/quota/dquot.c (ffffffff8129e3a2)
Location: fs/quota/dquot.c:810
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
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
In fs/quota/dquot.c (ffffffff812b3d02)
Location: fs/quota/dquot.c:807
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
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
In fs/quota/dquot.c (ffffffff812c0ebb)
Location: fs/quota/dquot.c:808
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
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
In fs/quota/dquot.c (ffffffff812e4c2e)
Location: fs/quota/dquot.c:815
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
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
In fs/quota/dquot.c (ffffffff8131234f)
Location: fs/quota/dquot.c:812
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
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
In fs/quota/dquot.c (ffffffff81328ecf)
Location: fs/quota/dquot.c:812
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
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
In fs/quota/dquot.c (ffffffff81350a3d)
Location: fs/quota/dquot.c:818
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
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
In fs/quota/dquot.c (ffffffff81368dbd)
Location: fs/quota/dquot.c:819
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dquot *get_empty_dquot(struct super_block *sb, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813ae960)
Location: fs/quota/dquot.c:817
Inline: False
Direct callers:
  - fs/quota/dquot.c:dqget
```
**Symbols:**

```
ffffffff813ae960-ffffffff813aea19: get_empty_dquot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dquot *get_empty_dquot(struct super_block *sb, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813bff50)
Location: fs/quota/dquot.c:818
Inline: False
Direct callers:
  - fs/quota/dquot.c:dqget
```
**Symbols:**

```
ffffffff813bff50-ffffffff813c0009: get_empty_dquot (STB_LOCAL)
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
In fs/quota/dquot.c (ffffffff813c922f)
Location: fs/quota/dquot.c:816
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
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
In fs/quota/dquot.c (ffffffff81419a9c)
Location: fs/quota/dquot.c:821
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
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
In fs/quota/dquot.c (ffffffff81490507)
Location: fs/quota/dquot.c:831
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
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
In fs/quota/dquot.c (ffffffff81524087)
Location: fs/quota/dquot.c:831
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
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
In fs/quota/dquot.c (ffffffff8155c48f)
Location: fs/quota/dquot.c:889
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
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
In fs/quota/dquot.c (ffffffff81592c4f)
Location: fs/quota/dquot.c:895
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
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
In fs/quota/dquot.c (ffff8000104302d0)
Location: fs/quota/dquot.c:819
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
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
In fs/quota/dquot.c (c05f8f24)
Location: fs/quota/dquot.c:819
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
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
In fs/quota/dquot.c (c000000000541f78)
Location: fs/quota/dquot.c:819
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
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
In fs/quota/dquot.c (ffffffe0002cd112)
Location: fs/quota/dquot.c:819
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
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
In fs/quota/dquot.c (ffffffff8136139d)
Location: fs/quota/dquot.c:819
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
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
In fs/quota/dquot.c (ffffffff8135203d)
Location: fs/quota/dquot.c:819
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
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
In fs/quota/dquot.c (ffffffff8135ee6d)
Location: fs/quota/dquot.c:819
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
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
In fs/quota/dquot.c (ffffffff81371894)
Location: fs/quota/dquot.c:819
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
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
