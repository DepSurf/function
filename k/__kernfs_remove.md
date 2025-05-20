# Function: <code>__kernfs_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __kernfs_remove(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8128a040)
Location: fs/kernfs/dir.c:1180
Inline: True
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
```
**Symbols:**

```
ffffffff8128a040-ffffffff8128a29d: __kernfs_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __kernfs_remove(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812b7470)
Location: fs/kernfs/dir.c:1228
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove
```
**Symbols:**

```
ffffffff812b7470-ffffffff812b76c4: __kernfs_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __kernfs_remove(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812ccc80)
Location: fs/kernfs/dir.c:1179
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove
```
**Symbols:**

```
ffffffff812ccc80-ffffffff812ccec4: __kernfs_remove (STB_LOCAL)
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
In fs/kernfs/dir.c (ffffffff812db14b)
Location: fs/kernfs/dir.c:1189
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove
```
**Symbols:**

```
ffffffff812da2d0-ffffffff812da4b4: __kernfs_remove.part.12 (STB_LOCAL)
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
In fs/kernfs/dir.c (ffffffff812ffa3b)
Location: fs/kernfs/dir.c:1254
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove
```
**Symbols:**

```
ffffffff812feb30-ffffffff812fed14: __kernfs_remove.part.12 (STB_LOCAL)
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
In fs/kernfs/dir.c (ffffffff8132d6eb)
Location: fs/kernfs/dir.c:1277
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove
```
**Symbols:**

```
ffffffff8132c5f0-ffffffff8132c7cf: __kernfs_remove.part.15 (STB_LOCAL)
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
In fs/kernfs/dir.c (ffffffff81344a8b)
Location: fs/kernfs/dir.c:1277
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove
```
**Symbols:**

```
ffffffff81343a70-ffffffff81343c4f: __kernfs_remove.part.15 (STB_LOCAL)
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
In fs/kernfs/dir.c (ffffffff8136ccaf)
Location: fs/kernfs/dir.c:1278
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove
```
**Symbols:**

```
ffffffff8136bce0-ffffffff8136bebf: __kernfs_remove.part.0 (STB_LOCAL)
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
In fs/kernfs/dir.c (ffffffff81384e5f)
Location: fs/kernfs/dir.c:1278
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove
```
**Symbols:**

```
ffffffff81383eb0-ffffffff8138408f: __kernfs_remove.part.0 (STB_LOCAL)
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
In fs/kernfs/dir.c (ffffffff813cf98f)
Location: fs/kernfs/dir.c:1282
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_destroy_root
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_destroy_root
```
**Symbols:**

```
ffffffff813ce810-ffffffff813ce9f4: __kernfs_remove.part.0 (STB_LOCAL)
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
In fs/kernfs/dir.c (ffffffff813e15bf)
Location: fs/kernfs/dir.c:1281
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_destroy_root
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_destroy_root
```
**Symbols:**

```
ffffffff813e0440-ffffffff813e0624: __kernfs_remove.part.0 (STB_LOCAL)
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
In fs/kernfs/dir.c (ffffffff813e81ef)
Location: fs/kernfs/dir.c:1283
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_destroy_root
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_destroy_root
```
**Symbols:**

```
ffffffff813e6eb0-ffffffff813e7155: __kernfs_remove.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81439f2f)
Location: fs/kernfs/dir.c:1310
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_destroy_root
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_destroy_root
```
**Symbols:**

```
ffffffff81438a60-ffffffff81438d0a: __kernfs_remove.part.0 (STB_LOCAL)
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
In fs/kernfs/dir.c (ffffffff814b50b3)
Location: fs/kernfs/dir.c:1342
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove
```
**Symbols:**

```
ffffffff814b3ae0-ffffffff814b3de5: __kernfs_remove.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8154c10c)
Location: fs/kernfs/dir.c:1418
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove
```
**Symbols:**

```
ffffffff8154a970-ffffffff8154abb3: __kernfs_remove.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81583dcc)
Location: fs/kernfs/dir.c:1422
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove
```
**Symbols:**

```
ffffffff81582580-ffffffff81582803: __kernfs_remove.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/kernfs/dir.c (ffffffff815bc8ac)
Location: fs/kernfs/dir.c:1438
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove
```
**Symbols:**

```
ffffffff815bb1f0-ffffffff815bb43f: __kernfs_remove.part.0 (STB_LOCAL)
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
In fs/kernfs/dir.c (ffff800010453e6c)
Location: fs/kernfs/dir.c:1278
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove
```
**Symbols:**

```
ffff800010452430-ffff800010452640: __kernfs_remove.part.0 (STB_LOCAL)
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
In fs/kernfs/dir.c (c0616990)
Location: fs/kernfs/dir.c:1278
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove
```
**Symbols:**

```
c061556c-c06157e8: __kernfs_remove.part.0 (STB_LOCAL)
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
In fs/kernfs/dir.c (c00000000056d448)
Location: fs/kernfs/dir.c:1278
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove
```
**Symbols:**

```
c00000000056b7b0-c00000000056ba80: __kernfs_remove.part.0 (STB_LOCAL)
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
In fs/kernfs/dir.c (ffffffe0002e6378)
Location: fs/kernfs/dir.c:1278
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove
```
**Symbols:**

```
ffffffe0002e4f7a-ffffffe0002e5176: __kernfs_remove.part.0 (STB_LOCAL)
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
In fs/kernfs/dir.c (ffffffff8137d43f)
Location: fs/kernfs/dir.c:1278
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove
```
**Symbols:**

```
ffffffff8137c490-ffffffff8137c66f: __kernfs_remove.part.0 (STB_LOCAL)
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
In fs/kernfs/dir.c (ffffffff8136deff)
Location: fs/kernfs/dir.c:1278
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove
```
**Symbols:**

```
ffffffff8136cf60-ffffffff8136d13f: __kernfs_remove.part.0 (STB_LOCAL)
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
In fs/kernfs/dir.c (ffffffff8137af0f)
Location: fs/kernfs/dir.c:1278
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove
```
**Symbols:**

```
ffffffff81379f60-ffffffff8137a13f: __kernfs_remove.part.0 (STB_LOCAL)
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
In fs/kernfs/dir.c (ffffffff8138ea0f)
Location: fs/kernfs/dir.c:1278
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_remove
```
**Symbols:**

```
ffffffff8138da30-ffffffff8138dc0a: __kernfs_remove.part.0 (STB_LOCAL)
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
</ul>
