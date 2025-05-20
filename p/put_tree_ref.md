# Function: <code>put_tree_ref</code>

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
In kernel/auditsc.c (ffffffff81127f26)
Location: kernel/auditsc.c:210
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
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
In kernel/auditsc.c (ffffffff81130110)
Location: kernel/auditsc.c:211
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
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
In kernel/auditsc.c (ffffffff81139e80)
Location: kernel/auditsc.c:211
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
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
In kernel/auditsc.c (ffffffff8113b50e)
Location: kernel/auditsc.c:212
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
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
In kernel/auditsc.c (ffffffff8114826b)
Location: kernel/auditsc.c:212
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
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
In kernel/auditsc.c (ffffffff81156c6b)
Location: kernel/auditsc.c:212
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
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
In kernel/auditsc.c (ffffffff8116289b)
Location: kernel/auditsc.c:211
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
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
In kernel/auditsc.c (ffffffff8116e697)
Location: kernel/auditsc.c:211
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
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
In kernel/auditsc.c (ffffffff8117a517)
Location: kernel/auditsc.c:211
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int put_tree_ref(struct audit_context *ctx, struct audit_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118f418)
Location: kernel/auditsc.c:222
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:handle_path
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
```
**Symbols:**

```
ffffffff8118c7b0-ffffffff8118c80e: put_tree_ref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int put_tree_ref(struct audit_context *ctx, struct audit_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118c68c)
Location: kernel/auditsc.c:238
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:handle_path
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
```
**Symbols:**

```
ffffffff81189980-ffffffff811899de: put_tree_ref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int put_tree_ref(struct audit_context *ctx, struct audit_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118d2db)
Location: kernel/auditsc.c:238
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
```
**Symbols:**

```
ffffffff8118a980-ffffffff8118a9de: put_tree_ref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int put_tree_ref(struct audit_context *ctx, struct audit_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811b5f8b)
Location: kernel/auditsc.c:239
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
```
**Symbols:**

```
ffffffff811b3560-ffffffff811b35be: put_tree_ref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int put_tree_ref(struct audit_context *ctx, struct audit_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811e97ad)
Location: kernel/auditsc.c:229
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
```
**Symbols:**

```
ffffffff811e59d0-ffffffff811e5a30: put_tree_ref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int put_tree_ref(struct audit_context *ctx, struct audit_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8122f72d)
Location: kernel/auditsc.c:229
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
```
**Symbols:**

```
ffffffff8122ba90-ffffffff8122baf0: put_tree_ref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int put_tree_ref(struct audit_context *ctx, struct audit_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff812452ac)
Location: kernel/auditsc.c:230
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
```
**Symbols:**

```
ffffffff81242070-ffffffff8124210c: put_tree_ref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int put_tree_ref(struct audit_context *ctx, struct audit_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8125f20b)
Location: kernel/auditsc.c:232
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
```
**Symbols:**

```
ffffffff8125be80-ffffffff8125bf1c: put_tree_ref (STB_LOCAL)
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
In kernel/auditsc.c (ffff8000101ef690)
Location: kernel/auditsc.c:211
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
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
In kernel/auditsc.c (c042faa8)
Location: kernel/auditsc.c:211
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
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
In kernel/auditsc.c (c000000000265704)
Location: kernel/auditsc.c:211
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
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
In kernel/auditsc.c (ffffffe0001633f8)
Location: kernel/auditsc.c:211
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
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
In kernel/auditsc.c (ffffffff81172b37)
Location: kernel/auditsc.c:211
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
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
In kernel/auditsc.c (ffffffff81165cd7)
Location: kernel/auditsc.c:211
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
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
In kernel/auditsc.c (ffffffff81170907)
Location: kernel/auditsc.c:211
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
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
In kernel/auditsc.c (ffffffff8117e152)
Location: kernel/auditsc.c:211
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
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
