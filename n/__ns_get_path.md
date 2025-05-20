# Function: <code>__ns_get_path</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *__ns_get_path(struct path *path, struct ns_common *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff8127d560)
Location: fs/nsfs.c:52
Inline: False
Direct callers:
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:ns_get_path
```
**Symbols:**

```
ffffffff8127d560-ffffffff8127d6d3: __ns_get_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *__ns_get_path(struct path *path, struct ns_common *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff8128b0f0)
Location: fs/nsfs.c:53
Inline: False
Direct callers:
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:ns_get_path
```
**Symbols:**

```
ffffffff8128b0f0-ffffffff8128b249: __ns_get_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *__ns_get_path(struct path *path, struct ns_common *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff812adc30)
Location: fs/nsfs.c:54
Inline: False
Direct callers:
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:ns_get_path
```
**Symbols:**

```
ffffffff812adc30-ffffffff812add95: __ns_get_path (STB_LOCAL)
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
In fs/nsfs.c (ffffffff812d5a90)
Location: fs/nsfs.c:54
Inline: True
Direct callers:
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:ns_get_path_cb
```
**Symbols:**

```
ffffffff812d5a90-ffffffff812d5c15: __ns_get_path.isra.4 (STB_LOCAL)
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
In fs/nsfs.c (ffffffff812eae60)
Location: fs/nsfs.c:54
Inline: True
Direct callers:
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:ns_get_path_cb
```
**Symbols:**

```
ffffffff812eae60-ffffffff812eafe5: __ns_get_path.isra.4 (STB_LOCAL)
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
In fs/nsfs.c (ffffffff813098e0)
Location: fs/nsfs.c:55
Inline: True
Direct callers:
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:ns_get_path_cb
```
**Symbols:**

```
ffffffff813098e0-ffffffff81309a58: __ns_get_path.isra.0 (STB_LOCAL)
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
In fs/nsfs.c (ffffffff8131c950)
Location: fs/nsfs.c:55
Inline: True
Direct callers:
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:ns_get_path_cb
```
**Symbols:**

```
ffffffff8131c950-ffffffff8131cac8: __ns_get_path.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __ns_get_path(struct path *path, struct ns_common *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff813565e0)
Location: fs/nsfs.c:58
Inline: False
Direct callers:
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:ns_get_path
  - fs/nsfs.c:ns_get_path_cb
```
**Symbols:**

```
ffffffff813565e0-ffffffff81356728: __ns_get_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __ns_get_path(struct path *path, struct ns_common *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81362f80)
Location: fs/nsfs.c:58
Inline: False
Direct callers:
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:ns_get_path
  - fs/nsfs.c:ns_get_path_cb
```
**Symbols:**

```
ffffffff81362f80-ffffffff813630d3: __ns_get_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __ns_get_path(struct path *path, struct ns_common *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81369a20)
Location: fs/nsfs.c:58
Inline: False
Direct callers:
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:ns_get_path
  - fs/nsfs.c:ns_get_path_cb
```
**Symbols:**

```
ffffffff81369a20-ffffffff81369b73: __ns_get_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __ns_get_path(struct path *path, struct ns_common *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff813b8710)
Location: fs/nsfs.c:58
Inline: False
Direct callers:
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:ns_get_path
  - fs/nsfs.c:ns_get_path_cb
```
**Symbols:**

```
ffffffff813b8710-ffffffff813b8863: __ns_get_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __ns_get_path(struct path *path, struct ns_common *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff8143dfe0)
Location: fs/nsfs.c:58
Inline: False
Direct callers:
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:ns_get_path
  - fs/nsfs.c:ns_get_path_cb
```
**Symbols:**

```
ffffffff8143dfe0-ffffffff8143e136: __ns_get_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __ns_get_path(struct path *path, struct ns_common *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff814cc9f0)
Location: fs/nsfs.c:58
Inline: False
Direct callers:
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:ns_get_path
  - fs/nsfs.c:ns_get_path_cb
```
**Symbols:**

```
ffffffff814cc9f0-ffffffff814ccb46: __ns_get_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __ns_get_path(struct path *path, struct ns_common *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81502c30)
Location: fs/nsfs.c:59
Inline: False
Direct callers:
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:ns_get_path
  - fs/nsfs.c:ns_get_path_cb
```
**Symbols:**

```
ffffffff81502c30-ffffffff81502d86: __ns_get_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __ns_get_path(struct path *path, struct ns_common *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81537880)
Location: fs/nsfs.c:59
Inline: False
Direct callers:
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:ns_get_path
  - fs/nsfs.c:ns_get_path_cb
```
**Symbols:**

```
ffffffff81537880-ffffffff815379a4: __ns_get_path (STB_LOCAL)
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
In fs/nsfs.c (ffff8000103d45c0)
Location: fs/nsfs.c:55
Inline: True
Direct callers:
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:ns_get_path_cb
```
**Symbols:**

```
ffff8000103d45c0-ffff8000103d4740: __ns_get_path.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *__ns_get_path(struct path *path, struct ns_common *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (c05ae4d0)
Location: fs/nsfs.c:55
Inline: False
Direct callers:
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:ns_get_path_cb
```
**Symbols:**

```
c05ae4d0-c05ae69c: __ns_get_path (STB_LOCAL)
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
In fs/nsfs.c (c0000000004d7210)
Location: fs/nsfs.c:55
Inline: True
Direct callers:
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:ns_get_path_cb
```
**Symbols:**

```
c0000000004d7210-c0000000004d7448: __ns_get_path.isra.0 (STB_LOCAL)
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
In fs/nsfs.c (ffffffe00028ea8e)
Location: fs/nsfs.c:55
Inline: True
Direct callers:
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:ns_get_path_cb
```
**Symbols:**

```
ffffffe00028ea8e-ffffffe00028ebba: __ns_get_path.isra.0 (STB_LOCAL)
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
In fs/nsfs.c (ffffffff81314f30)
Location: fs/nsfs.c:55
Inline: True
Direct callers:
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:ns_get_path_cb
```
**Symbols:**

```
ffffffff81314f30-ffffffff813150a8: __ns_get_path.isra.0 (STB_LOCAL)
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
In fs/nsfs.c (ffffffff81305b20)
Location: fs/nsfs.c:55
Inline: True
Direct callers:
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:ns_get_path_cb
```
**Symbols:**

```
ffffffff81305b20-ffffffff81305c98: __ns_get_path.isra.0 (STB_LOCAL)
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
In fs/nsfs.c (ffffffff81312d20)
Location: fs/nsfs.c:55
Inline: True
Direct callers:
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:ns_get_path_cb
```
**Symbols:**

```
ffffffff81312d20-ffffffff81312e98: __ns_get_path.isra.0 (STB_LOCAL)
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
In fs/nsfs.c (ffffffff81324550)
Location: fs/nsfs.c:55
Inline: True
Direct callers:
  - fs/nsfs.c:open_related_ns
  - fs/nsfs.c:ns_get_path_cb
```
**Symbols:**

```
ffffffff81324550-ffffffff813246e6: __ns_get_path.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
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
</ul>
