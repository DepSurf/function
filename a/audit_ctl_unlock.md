# Function: <code>audit_ctl_unlock</code>

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
void audit_ctl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8115237b)
Location: kernel/audit.c:254
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
ffffffff8114f620-ffffffff8114f642: audit_ctl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void audit_ctl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8115f028)
Location: kernel/audit.c:250
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
ffffffff8115c300-ffffffff8115c322: audit_ctl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void audit_ctl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116b3ba)
Location: kernel/audit.c:237
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
ffffffff811689d0-ffffffff811689f2: audit_ctl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void audit_ctl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8117729a)
Location: kernel/audit.c:237
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
ffffffff81174870-ffffffff81174892: audit_ctl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void audit_ctl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81189e7a)
Location: kernel/audit.c:238
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
ffffffff811868e0-ffffffff81186902: audit_ctl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void audit_ctl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8118717a)
Location: kernel/audit.c:243
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
ffffffff81183bf0-ffffffff81183c12: audit_ctl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void audit_ctl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8118822a)
Location: kernel/audit.c:243
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
ffffffff81184b20-ffffffff81184b42: audit_ctl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void audit_ctl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811b065a)
Location: kernel/audit.c:243
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
ffffffff811ace40-ffffffff811ace62: audit_ctl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void audit_ctl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811e27fa)
Location: kernel/audit.c:245
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
ffffffff811dea70-ffffffff811dea98: audit_ctl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void audit_ctl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff812286aa)
Location: kernel/audit.c:245
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
ffffffff81224660-ffffffff81224688: audit_ctl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void audit_ctl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8123ecaa)
Location: kernel/audit.c:245
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
ffffffff8123ac30-ffffffff8123ac58: audit_ctl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void audit_ctl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81258af0)
Location: kernel/audit.c:244
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
ffffffff81254af0-ffffffff81254b18: audit_ctl_unlock (STB_GLOBAL)
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
void audit_ctl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffff8000101ec238)
Location: kernel/audit.c:237
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
ffff8000101e9358-ffff8000101e9384: audit_ctl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void audit_ctl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c042be60)
Location: kernel/audit.c:237
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
c04292b4-c04292e4: audit_ctl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void audit_ctl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c00000000025db7c)
Location: kernel/audit.c:237
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
c00000000025a0e0-c00000000025a128: audit_ctl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void audit_ctl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffe000160960)
Location: kernel/audit.c:237
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
ffffffe00015e162-ffffffe00015e190: audit_ctl_unlock (STB_GLOBAL)
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
void audit_ctl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116f8ba)
Location: kernel/audit.c:237
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
ffffffff8116ce90-ffffffff8116ceb2: audit_ctl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void audit_ctl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81162a5a)
Location: kernel/audit.c:237
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
ffffffff81160030-ffffffff81160052: audit_ctl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void audit_ctl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116d68a)
Location: kernel/audit.c:237
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
ffffffff8116ac60-ffffffff8116ac82: audit_ctl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void audit_ctl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8117ae7a)
Location: kernel/audit.c:237
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
ffffffff81178450-ffffffff81178472: audit_ctl_unlock (STB_GLOBAL)
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
