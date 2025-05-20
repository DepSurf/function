# Function: <code>audit_ctl_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void audit_ctl_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8115230f)
Location: kernel/audit.c:245
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
Direct callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:prune_tree_thread
```
**Symbols:**

```
ffffffff8114f5f0-ffffffff8114f617: audit_ctl_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void audit_ctl_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8115efbc)
Location: kernel/audit.c:241
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
Direct callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:prune_tree_thread
```
**Symbols:**

```
ffffffff8115c2d0-ffffffff8115c2f7: audit_ctl_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void audit_ctl_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116b34c)
Location: kernel/audit.c:228
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
Direct callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:prune_tree_thread
```
**Symbols:**

```
ffffffff811689a0-ffffffff811689c7: audit_ctl_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void audit_ctl_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8117722c)
Location: kernel/audit.c:228
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
Direct callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:prune_tree_thread
```
**Symbols:**

```
ffffffff81174840-ffffffff81174867: audit_ctl_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void audit_ctl_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81189e0c)
Location: kernel/audit.c:229
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
Direct callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:prune_tree_thread
```
**Symbols:**

```
ffffffff811868b0-ffffffff811868d7: audit_ctl_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void audit_ctl_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8118710c)
Location: kernel/audit.c:234
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
Direct callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:prune_tree_thread
```
**Symbols:**

```
ffffffff81183bc0-ffffffff81183be7: audit_ctl_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void audit_ctl_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811881bc)
Location: kernel/audit.c:234
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
Direct callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:prune_tree_thread
```
**Symbols:**

```
ffffffff81184af0-ffffffff81184b17: audit_ctl_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void audit_ctl_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811b0636)
Location: kernel/audit.c:234
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
Direct callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:prune_tree_thread
```
**Symbols:**

```
ffffffff811ace10-ffffffff811ace37: audit_ctl_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void audit_ctl_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811e27d6)
Location: kernel/audit.c:236
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
Direct callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:prune_tree_thread
```
**Symbols:**

```
ffffffff811dea40-ffffffff811dea6f: audit_ctl_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void audit_ctl_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81228686)
Location: kernel/audit.c:236
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
Direct callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:prune_tree_thread
```
**Symbols:**

```
ffffffff81224620-ffffffff8122464f: audit_ctl_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void audit_ctl_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8123ec86)
Location: kernel/audit.c:236
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
Direct callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:prune_tree_thread
```
**Symbols:**

```
ffffffff8123abf0-ffffffff8123ac1f: audit_ctl_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void audit_ctl_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81258acc)
Location: kernel/audit.c:235
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
Direct callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:prune_tree_thread
```
**Symbols:**

```
ffffffff81254ab0-ffffffff81254adf: audit_ctl_lock (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void audit_ctl_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffff8000101ec1c8)
Location: kernel/audit.c:228
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
Direct callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:prune_tree_thread
```
**Symbols:**

```
ffff8000101e9318-ffff8000101e9354: audit_ctl_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void audit_ctl_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c042bde0)
Location: kernel/audit.c:228
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
Direct callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:prune_tree_thread
```
**Symbols:**

```
c0429278-c04292b4: audit_ctl_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void audit_ctl_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c00000000025daf0)
Location: kernel/audit.c:228
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
Direct callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:prune_tree_thread
```
**Symbols:**

```
c00000000025a090-c00000000025a0d8: audit_ctl_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void audit_ctl_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffe0001608f2)
Location: kernel/audit.c:228
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
Direct callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:prune_tree_thread
```
**Symbols:**

```
ffffffe00015e12e-ffffffe00015e162: audit_ctl_lock (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void audit_ctl_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116f84c)
Location: kernel/audit.c:228
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
Direct callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:prune_tree_thread
```
**Symbols:**

```
ffffffff8116ce60-ffffffff8116ce87: audit_ctl_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void audit_ctl_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811629ec)
Location: kernel/audit.c:228
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
Direct callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:prune_tree_thread
```
**Symbols:**

```
ffffffff81160000-ffffffff81160027: audit_ctl_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void audit_ctl_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116d61c)
Location: kernel/audit.c:228
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
Direct callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:prune_tree_thread
```
**Symbols:**

```
ffffffff8116ac30-ffffffff8116ac57: audit_ctl_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void audit_ctl_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8117ae0c)
Location: kernel/audit.c:228
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
Direct callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:prune_tree_thread
```
**Symbols:**

```
ffffffff81178420-ffffffff81178447: audit_ctl_lock (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
