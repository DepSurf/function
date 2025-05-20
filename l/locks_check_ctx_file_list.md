# Function: <code>locks_check_ctx_file_list</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void locks_check_ctx_file_list(struct file *filp, struct list_head *list, char *list_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812d2d40)
Location: fs/locks.c:275
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
ffffffff812d2d40-ffffffff812d2dde: locks_check_ctx_file_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void locks_check_ctx_file_list(struct file *filp, struct list_head *list, char *list_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/locks.c (0)
Location: fs/locks.c:275
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
ffffffff812fd670-ffffffff812fd6cc: locks_check_ctx_file_list (STB_LOCAL)
ffffffff81301667-ffffffff813016ab: locks_check_ctx_file_list.cold.44 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void locks_check_ctx_file_list(struct file *filp, struct list_head *list, char *list_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/locks.c (0)
Location: fs/locks.c:306
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
ffffffff81312ef0-ffffffff81312f48: locks_check_ctx_file_list (STB_LOCAL)
ffffffff81317153-ffffffff81317197: locks_check_ctx_file_list.cold.43 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void locks_check_ctx_file_list(struct file *filp, struct list_head *list, char *list_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/locks.c (0)
Location: fs/locks.c:307
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
ffffffff8133a6f0-ffffffff8133a741: locks_check_ctx_file_list (STB_LOCAL)
ffffffff8133ea0f-ffffffff8133ea50: locks_check_ctx_file_list.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void locks_check_ctx_file_list(struct file *filp, struct list_head *list, char *list_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/locks.c (0)
Location: fs/locks.c:308
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
ffffffff81352c20-ffffffff81352c71: locks_check_ctx_file_list (STB_LOCAL)
ffffffff81356fff-ffffffff81357040: locks_check_ctx_file_list.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void locks_check_ctx_file_list(struct file *filp, struct list_head *list, char *list_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/locks.c (0)
Location: fs/locks.c:308
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
ffffffff81399560-ffffffff813995b1: locks_check_ctx_file_list (STB_LOCAL)
ffffffff8139e2ad-ffffffff8139e2ee: locks_check_ctx_file_list.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void locks_check_ctx_file_list(struct file *filp, struct list_head *list, char *list_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/locks.c (0)
Location: fs/locks.c:308
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
ffffffff813ab040-ffffffff813ab091: locks_check_ctx_file_list (STB_LOCAL)
ffffffff81beb999-ffffffff81beb9da: locks_check_ctx_file_list.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void locks_check_ctx_file_list(struct file *filp, struct list_head *list, char *list_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/locks.c (0)
Location: fs/locks.c:308
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
ffffffff813b2510-ffffffff813b2561: locks_check_ctx_file_list (STB_LOCAL)
ffffffff81bdd9fb-ffffffff81bdda3c: locks_check_ctx_file_list.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void locks_check_ctx_file_list(struct file *filp, struct list_head *list, char *list_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/locks.c (0)
Location: fs/locks.c:308
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
ffffffff81402100-ffffffff81402151: locks_check_ctx_file_list (STB_LOCAL)
ffffffff81cc7404-ffffffff81cc7445: locks_check_ctx_file_list.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void locks_check_ctx_file_list(struct file *filp, struct list_head *list, char *list_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/locks.c (0)
Location: fs/locks.c:232
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
ffffffff814769d0-ffffffff81476a35: locks_check_ctx_file_list (STB_LOCAL)
ffffffff81e79983-ffffffff81e799c4: locks_check_ctx_file_list.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void locks_check_ctx_file_list(struct file *filp, struct list_head *list, char *list_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81509090)
Location: fs/locks.c:232
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
ffffffff81509090-ffffffff8150913c: locks_check_ctx_file_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void locks_check_ctx_file_list(struct file *filp, struct list_head *list, char *list_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81540650)
Location: fs/locks.c:233
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
ffffffff81540650-ffffffff815406ff: locks_check_ctx_file_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void locks_check_ctx_file_list(struct file *filp, struct list_head *list, char *list_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81575b30)
Location: fs/locks.c:232
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
ffffffff81575b30-ffffffff81575bdf: locks_check_ctx_file_list (STB_LOCAL)
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
void locks_check_ctx_file_list(struct file *filp, struct list_head *list, char *list_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffff800010414740)
Location: fs/locks.c:308
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
ffff800010414740-ffff8000104147f4: locks_check_ctx_file_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void locks_check_ctx_file_list(struct file *filp, struct list_head *list, char *list_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c05e1238)
Location: fs/locks.c:308
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
c05e1238-c05e12e4: locks_check_ctx_file_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void locks_check_ctx_file_list(struct file *filp, struct list_head *list, char *list_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c0000000005237c0)
Location: fs/locks.c:308
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
c0000000005237c0-c0000000005238a8: locks_check_ctx_file_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void locks_check_ctx_file_list(struct file *filp, struct list_head *list, char *list_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffe0002bc3a2)
Location: fs/locks.c:308
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
ffffffe0002bc3a2-ffffffe0002bc43c: locks_check_ctx_file_list (STB_LOCAL)
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
void locks_check_ctx_file_list(struct file *filp, struct list_head *list, char *list_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/locks.c (0)
Location: fs/locks.c:308
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
ffffffff8134b200-ffffffff8134b251: locks_check_ctx_file_list (STB_LOCAL)
ffffffff8134f5df-ffffffff8134f620: locks_check_ctx_file_list.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void locks_check_ctx_file_list(struct file *filp, struct list_head *list, char *list_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/locks.c (0)
Location: fs/locks.c:308
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
ffffffff8133bee0-ffffffff8133bf31: locks_check_ctx_file_list (STB_LOCAL)
ffffffff813402bf-ffffffff81340300: locks_check_ctx_file_list.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void locks_check_ctx_file_list(struct file *filp, struct list_head *list, char *list_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/locks.c (0)
Location: fs/locks.c:308
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
ffffffff81348cd0-ffffffff81348d21: locks_check_ctx_file_list (STB_LOCAL)
ffffffff8134d0af-ffffffff8134d0f0: locks_check_ctx_file_list.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void locks_check_ctx_file_list(struct file *filp, struct list_head *list, char *list_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/locks.c (0)
Location: fs/locks.c:308
Inline: False
Direct callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
```
**Symbols:**

```
ffffffff8135c0f0-ffffffff8135c141: locks_check_ctx_file_list (STB_LOCAL)
ffffffff8136063a-ffffffff8136067b: locks_check_ctx_file_list.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
