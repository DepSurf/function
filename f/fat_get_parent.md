# Function: <code>fat_get_parent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *fat_get_parent(struct dentry *child_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff812fe760)
Location: fs/fat/nfs.c:271
Inline: False
```
**Symbols:**

```
ffffffff812fe760-ffffffff812fe94d: fat_get_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *fat_get_parent(struct dentry *child_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff81332760)
Location: fs/fat/nfs.c:271
Inline: False
```
**Symbols:**

```
ffffffff81332760-ffffffff81332946: fat_get_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *fat_get_parent(struct dentry *child_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff81348500)
Location: fs/fat/nfs.c:271
Inline: False
```
**Symbols:**

```
ffffffff81348500-ffffffff813486e6: fat_get_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *fat_get_parent(struct dentry *child_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff8135d070)
Location: fs/fat/nfs.c:271
Inline: False
```
**Symbols:**

```
ffffffff8135d070-ffffffff8135d24a: fat_get_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *fat_get_parent(struct dentry *child_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff81381d70)
Location: fs/fat/nfs.c:271
Inline: False
```
**Symbols:**

```
ffffffff81381d70-ffffffff81381f4a: fat_get_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct dentry *fat_get_parent(struct dentry *child_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/nfs.c (0)
Location: fs/fat/nfs.c:271
Inline: False
```
**Symbols:**

```
ffffffff813b0b40-ffffffff813b0cfe: fat_get_parent (STB_LOCAL)
ffffffff813b0e04-ffffffff813b0e1f: fat_get_parent.cold.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct dentry *fat_get_parent(struct dentry *child_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/nfs.c (0)
Location: fs/fat/nfs.c:271
Inline: False
```
**Symbols:**

```
ffffffff813ca240-ffffffff813ca3fe: fat_get_parent (STB_LOCAL)
ffffffff813ca464-ffffffff813ca47f: fat_get_parent.cold.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct dentry *fat_get_parent(struct dentry *child_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/nfs.c (0)
Location: fs/fat/nfs.c:262
Inline: False
```
**Symbols:**

```
ffffffff813f4db0-ffffffff813f4f8d: fat_get_parent (STB_LOCAL)
ffffffff813f4ff4-ffffffff813f500f: fat_get_parent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct dentry *fat_get_parent(struct dentry *child_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/nfs.c (0)
Location: fs/fat/nfs.c:262
Inline: False
```
**Symbols:**

```
ffffffff8140ec80-ffffffff8140ee5d: fat_get_parent (STB_LOCAL)
ffffffff8140eec4-ffffffff8140eedf: fat_get_parent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *fat_get_parent(struct dentry *child_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff8145c940)
Location: fs/fat/nfs.c:262
Inline: False
```
**Symbols:**

```
ffffffff8145c940-ffffffff8145ca0e: fat_get_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *fat_get_parent(struct dentry *child_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff81478670)
Location: fs/fat/nfs.c:262
Inline: False
```
**Symbols:**

```
ffffffff81478670-ffffffff8147873e: fat_get_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dentry *fat_get_parent(struct dentry *child_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff8147e0e0)
Location: fs/fat/nfs.c:262
Inline: False
```
**Symbols:**

```
ffffffff8147e0e0-ffffffff8147e1ae: fat_get_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dentry *fat_get_parent(struct dentry *child_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff814d5880)
Location: fs/fat/nfs.c:262
Inline: False
```
**Symbols:**

```
ffffffff814d5880-ffffffff814d594e: fat_get_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dentry *fat_get_parent(struct dentry *child_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff815629a0)
Location: fs/fat/nfs.c:262
Inline: False
```
**Symbols:**

```
ffffffff815629a0-ffffffff81562a82: fat_get_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *fat_get_parent(struct dentry *child_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff816053d0)
Location: fs/fat/nfs.c:262
Inline: False
```
**Symbols:**

```
ffffffff816053d0-ffffffff816054b2: fat_get_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dentry *fat_get_parent(struct dentry *child_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff8163d2e0)
Location: fs/fat/nfs.c:262
Inline: False
```
**Symbols:**

```
ffffffff8163d2e0-ffffffff8163d3c2: fat_get_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *fat_get_parent(struct dentry *child_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff81676850)
Location: fs/fat/nfs.c:262
Inline: False
```
**Symbols:**

```
ffffffff81676850-ffffffff81676932: fat_get_parent (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct dentry *fat_get_parent(struct dentry *child_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffff8000104efb00)
Location: fs/fat/nfs.c:262
Inline: False
```
**Symbols:**

```
ffff8000104efb00-ffff8000104efcf0: fat_get_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *fat_get_parent(struct dentry *child_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (c06ad108)
Location: fs/fat/nfs.c:262
Inline: False
```
**Symbols:**

```
c06ad108-c06ad30c: fat_get_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *fat_get_parent(struct dentry *child_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (c00000000062e990)
Location: fs/fat/nfs.c:262
Inline: False
```
**Symbols:**

```
c00000000062e990-c00000000062ec40: fat_get_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *fat_get_parent(struct dentry *child_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffe00035f906)
Location: fs/fat/nfs.c:262
Inline: False
```
**Symbols:**

```
ffffffe00035f906-ffffffe00035fac6: fat_get_parent (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct dentry *fat_get_parent(struct dentry *child_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/nfs.c (0)
Location: fs/fat/nfs.c:262
Inline: False
```
**Symbols:**

```
ffffffff81407260-ffffffff8140743d: fat_get_parent (STB_LOCAL)
ffffffff814074a4-ffffffff814074bf: fat_get_parent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct dentry *fat_get_parent(struct dentry *child_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/nfs.c (0)
Location: fs/fat/nfs.c:262
Inline: False
```
**Symbols:**

```
ffffffff813f7ce0-ffffffff813f7ebd: fat_get_parent (STB_LOCAL)
ffffffff813f7f24-ffffffff813f7f3f: fat_get_parent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct dentry *fat_get_parent(struct dentry *child_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/nfs.c (0)
Location: fs/fat/nfs.c:262
Inline: False
```
**Symbols:**

```
ffffffff814045e0-ffffffff814047bd: fat_get_parent (STB_LOCAL)
ffffffff81404824-ffffffff8140483f: fat_get_parent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct dentry *fat_get_parent(struct dentry *child_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/nfs.c (0)
Location: fs/fat/nfs.c:262
Inline: False
```
**Symbols:**

```
ffffffff8141a260-ffffffff8141a43d: fat_get_parent (STB_LOCAL)
ffffffff8141a4a4-ffffffff8141a4bf: fat_get_parent.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
