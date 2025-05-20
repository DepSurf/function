# Function: <code>kernfs_drain</code>

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
In fs/kernfs/dir.c (ffffffff8128a0c3)
Location: fs/kernfs/dir.c:497
Inline: True
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
In fs/kernfs/dir.c (ffffffff812b74eb)
Location: fs/kernfs/dir.c:496
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_remove
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
In fs/kernfs/dir.c (ffffffff812ccde3)
Location: fs/kernfs/dir.c:446
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_remove
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
In fs/kernfs/dir.c (ffffffff812da3fa)
Location: fs/kernfs/dir.c:456
Inline: True
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
In fs/kernfs/dir.c (ffffffff812fec5a)
Location: fs/kernfs/dir.c:457
Inline: True
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
In fs/kernfs/dir.c (ffffffff8132c718)
Location: fs/kernfs/dir.c:457
Inline: True
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
In fs/kernfs/dir.c (ffffffff81343b98)
Location: fs/kernfs/dir.c:457
Inline: True
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
In fs/kernfs/dir.c (ffffffff8136be08)
Location: fs/kernfs/dir.c:456
Inline: True
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
In fs/kernfs/dir.c (ffffffff81383fd8)
Location: fs/kernfs/dir.c:457
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void kernfs_drain(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813cdf90)
Location: fs/kernfs/dir.c:457
Inline: False
```
**Symbols:**

```
ffffffff813cdf90-ffffffff813ce062: kernfs_drain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void kernfs_drain(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813dfbc0)
Location: fs/kernfs/dir.c:457
Inline: False
```
**Symbols:**

```
ffffffff813dfbc0-ffffffff813dfc92: kernfs_drain (STB_LOCAL)
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
In fs/kernfs/dir.c (ffffffff813e7089)
Location: fs/kernfs/dir.c:457
Inline: True
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
In fs/kernfs/dir.c (ffffffff81438c42)
Location: fs/kernfs/dir.c:459
Inline: True
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
In fs/kernfs/dir.c (ffffffff814b3cce)
Location: fs/kernfs/dir.c:466
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kernfs_drain(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8154a190)
Location: fs/kernfs/dir.c:477
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_show
```
**Symbols:**

```
ffffffff8154a190-ffffffff8154a2db: kernfs_drain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kernfs_drain(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81581dc0)
Location: fs/kernfs/dir.c:474
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_show
```
**Symbols:**

```
ffffffff81581dc0-ffffffff81581f0b: kernfs_drain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kernfs_drain(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff815ba860)
Location: fs/kernfs/dir.c:478
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_show
```
**Symbols:**

```
ffffffff815ba860-ffffffff815ba9ab: kernfs_drain (STB_LOCAL)
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
In fs/kernfs/dir.c (ffff80001045258c)
Location: fs/kernfs/dir.c:457
Inline: True
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
In fs/kernfs/dir.c (c06156f4)
Location: fs/kernfs/dir.c:457
Inline: True
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
In fs/kernfs/dir.c (c00000000056b970)
Location: fs/kernfs/dir.c:457
Inline: True
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
In fs/kernfs/dir.c (ffffffe0002e4fea)
Location: fs/kernfs/dir.c:457
Inline: True
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
In fs/kernfs/dir.c (ffffffff8137c5b8)
Location: fs/kernfs/dir.c:457
Inline: True
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
In fs/kernfs/dir.c (ffffffff8136d088)
Location: fs/kernfs/dir.c:457
Inline: True
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
In fs/kernfs/dir.c (ffffffff8137a088)
Location: fs/kernfs/dir.c:457
Inline: True
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
In fs/kernfs/dir.c (ffffffff8138db58)
Location: fs/kernfs/dir.c:457
Inline: True
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
