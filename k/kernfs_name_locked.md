# Function: <code>kernfs_name_locked</code>

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
In fs/kernfs/dir.c (ffffffff8128a385)
Location: fs/kernfs/dir.c:42
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_name
  - fs/kernfs/dir.c:pr_cont_kernfs_name
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
In fs/kernfs/dir.c (ffffffff812b788b)
Location: fs/kernfs/dir.c:42
Inline: True
Inline callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_name
  - fs/kernfs/dir.c:kernfs_name
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
In fs/kernfs/dir.c (ffffffff812cd01b)
Location: fs/kernfs/dir.c:42
Inline: True
Inline callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_name
  - fs/kernfs/dir.c:kernfs_name
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kernfs_name_locked(struct kernfs_node *kn, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812d9340)
Location: fs/kernfs/dir.c:42
Inline: False
Direct callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_name
  - fs/kernfs/dir.c:kernfs_name
```
**Symbols:**

```
ffffffff812d9340-ffffffff812d93ec: kernfs_name_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kernfs_name_locked(struct kernfs_node *kn, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812fdbb0)
Location: fs/kernfs/dir.c:43
Inline: False
Direct callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_name
  - fs/kernfs/dir.c:kernfs_name
```
**Symbols:**

```
ffffffff812fdbb0-ffffffff812fdc27: kernfs_name_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kernfs_name_locked(struct kernfs_node *kn, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8132b810)
Location: fs/kernfs/dir.c:43
Inline: False
Direct callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_name
  - fs/kernfs/dir.c:kernfs_name
```
**Symbols:**

```
ffffffff8132b810-ffffffff8132b886: kernfs_name_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kernfs_name_locked(struct kernfs_node *kn, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81342b70)
Location: fs/kernfs/dir.c:43
Inline: False
Direct callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_name
  - fs/kernfs/dir.c:kernfs_name
```
**Symbols:**

```
ffffffff81342b70-ffffffff81342be6: kernfs_name_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kernfs_name_locked(struct kernfs_node *kn, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136ae10)
Location: fs/kernfs/dir.c:42
Inline: False
Direct callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_name
  - fs/kernfs/dir.c:kernfs_name
```
**Symbols:**

```
ffffffff8136ae10-ffffffff8136ae80: kernfs_name_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kernfs_name_locked(struct kernfs_node *kn, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81382fd0)
Location: fs/kernfs/dir.c:42
Inline: False
Direct callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_name
  - fs/kernfs/dir.c:kernfs_name
```
**Symbols:**

```
ffffffff81382fd0-ffffffff81383040: kernfs_name_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kernfs_name_locked(struct kernfs_node *kn, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813cd920)
Location: fs/kernfs/dir.c:42
Inline: False
Direct callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_name
  - fs/kernfs/dir.c:kernfs_name
```
**Symbols:**

```
ffffffff813cd920-ffffffff813cd990: kernfs_name_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kernfs_name_locked(struct kernfs_node *kn, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813df550)
Location: fs/kernfs/dir.c:42
Inline: False
Direct callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_name
  - fs/kernfs/dir.c:kernfs_name
```
**Symbols:**

```
ffffffff813df550-ffffffff813df5c0: kernfs_name_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kernfs_name_locked(struct kernfs_node *kn, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813e61f0)
Location: fs/kernfs/dir.c:42
Inline: False
Direct callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_name
  - fs/kernfs/dir.c:kernfs_name
```
**Symbols:**

```
ffffffff813e61f0-ffffffff813e6260: kernfs_name_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kernfs_name_locked(struct kernfs_node *kn, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81437df0)
Location: fs/kernfs/dir.c:42
Inline: False
Direct callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_name
  - fs/kernfs/dir.c:kernfs_name
```
**Symbols:**

```
ffffffff81437df0-ffffffff81437e60: kernfs_name_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kernfs_name_locked(struct kernfs_node *kn, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff814b2b70)
Location: fs/kernfs/dir.c:49
Inline: False
Direct callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_name
```
**Symbols:**

```
ffffffff814b2b70-ffffffff814b2bfb: kernfs_name_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kernfs_name_locked(struct kernfs_node *kn, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81549790)
Location: fs/kernfs/dir.c:54
Inline: False
Direct callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_name
```
**Symbols:**

```
ffffffff81549790-ffffffff8154981b: kernfs_name_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kernfs_name_locked(struct kernfs_node *kn, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81581370)
Location: fs/kernfs/dir.c:54
Inline: False
Direct callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_name
```
**Symbols:**

```
ffffffff81581370-ffffffff815813ef: kernfs_name_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kernfs_name_locked(struct kernfs_node *kn, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff815b9e10)
Location: fs/kernfs/dir.c:54
Inline: False
Direct callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_name
```
**Symbols:**

```
ffffffff815b9e10-ffffffff815b9eae: kernfs_name_locked (STB_LOCAL)
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
int kernfs_name_locked(struct kernfs_node *kn, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffff800010451578)
Location: fs/kernfs/dir.c:42
Inline: False
Direct callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_name
  - fs/kernfs/dir.c:kernfs_name
```
**Symbols:**

```
ffff800010451578-ffff800010451620: kernfs_name_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kernfs_name_locked(struct kernfs_node *kn, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c06144cc)
Location: fs/kernfs/dir.c:42
Inline: False
Direct callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_name
  - fs/kernfs/dir.c:kernfs_name
```
**Symbols:**

```
c06144cc-c061454c: kernfs_name_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kernfs_name_locked(struct kernfs_node *kn, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c000000000569cd0)
Location: fs/kernfs/dir.c:42
Inline: False
Direct callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_name
  - fs/kernfs/dir.c:kernfs_name
```
**Symbols:**

```
c000000000569cd0-c000000000569d94: kernfs_name_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int kernfs_name_locked(struct kernfs_node *kn, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffe0002e484a)
Location: fs/kernfs/dir.c:42
Inline: True
Direct callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_name
  - fs/kernfs/dir.c:kernfs_name
```
**Symbols:**

```
ffffffe0002e484a-ffffffe0002e48ac: kernfs_name_locked (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int kernfs_name_locked(struct kernfs_node *kn, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8137b5b0)
Location: fs/kernfs/dir.c:42
Inline: False
Direct callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_name
  - fs/kernfs/dir.c:kernfs_name
```
**Symbols:**

```
ffffffff8137b5b0-ffffffff8137b620: kernfs_name_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kernfs_name_locked(struct kernfs_node *kn, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136c080)
Location: fs/kernfs/dir.c:42
Inline: False
Direct callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_name
  - fs/kernfs/dir.c:kernfs_name
```
**Symbols:**

```
ffffffff8136c080-ffffffff8136c0f0: kernfs_name_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kernfs_name_locked(struct kernfs_node *kn, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81379080)
Location: fs/kernfs/dir.c:42
Inline: False
Direct callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_name
  - fs/kernfs/dir.c:kernfs_name
```
**Symbols:**

```
ffffffff81379080-ffffffff813790f0: kernfs_name_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kernfs_name_locked(struct kernfs_node *kn, char *buf, size_t buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8138cb30)
Location: fs/kernfs/dir.c:42
Inline: False
Direct callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_name
  - fs/kernfs/dir.c:kernfs_name
```
**Symbols:**

```
ffffffff8138cb30-ffffffff8138cba0: kernfs_name_locked (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
