# Function: <code>kobj_kset_leave</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void kobj_kset_leave(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff813eb800)
Location: lib/kobject.c:176
Inline: False
Direct callers:
  - lib/kobject.c:kobject_del
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff813eb800-ffffffff813eb855: kobj_kset_leave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void kobj_kset_leave(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81431bf0)
Location: lib/kobject.c:176
Inline: False
Direct callers:
  - lib/kobject.c:kobject_del
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff81431bf0-ffffffff81431c45: kobj_kset_leave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void kobj_kset_leave(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8144de60)
Location: lib/kobject.c:176
Inline: False
Direct callers:
  - lib/kobject.c:kobject_del
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff8144de60-ffffffff8144deb5: kobj_kset_leave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void kobj_kset_leave(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff818ee280)
Location: lib/kobject.c:176
Inline: False
Direct callers:
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff818ee280-ffffffff818ee2d6: kobj_kset_leave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void kobj_kset_leave(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81974330)
Location: lib/kobject.c:176
Inline: False
Direct callers:
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff81974330-ffffffff81974386: kobj_kset_leave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void kobj_kset_leave(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff819d0850)
Location: lib/kobject.c:193
Inline: False
Direct callers:
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff819d0850-ffffffff819d08a5: kobj_kset_leave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void kobj_kset_leave(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a09e70)
Location: lib/kobject.c:193
Inline: False
Direct callers:
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff81a09e70-ffffffff81a09ec5: kobj_kset_leave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void kobj_kset_leave(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a796c0)
Location: lib/kobject.c:201
Inline: False
Direct callers:
  - lib/kobject.c:kobject_del
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff81a796c0-ffffffff81a79714: kobj_kset_leave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void kobj_kset_leave(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81ab0a20)
Location: lib/kobject.c:201
Inline: False
Direct callers:
  - lib/kobject.c:kobject_del
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff81ab0a20-ffffffff81ab0a74: kobj_kset_leave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff815eacac)
Location: lib/kobject.c:201
Inline: True
Inline callers:
  - lib/kobject.c:__kobject_del
  - lib/kobject.c:kobject_add_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8160f5c3)
Location: lib/kobject.c:201
Inline: True
Inline callers:
  - lib/kobject.c:__kobject_del
  - lib/kobject.c:kobject_add_internal
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
In lib/kobject.c (ffffffff815f2d03)
Location: lib/kobject.c:201
Inline: True
Inline callers:
  - lib/kobject.c:__kobject_del
  - lib/kobject.c:kobject_add_internal
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
In lib/kobject.c (ffffffff8165fee3)
Location: lib/kobject.c:201
Inline: True
Inline callers:
  - lib/kobject.c:__kobject_del
  - lib/kobject.c:kobject_add_internal
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
In lib/kobject.c (ffffffff817799c3)
Location: lib/kobject.c:169
Inline: True
Inline callers:
  - lib/kobject.c:__kobject_del
  - lib/kobject.c:kobject_add_internal
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
In lib/kobject.c (ffffffff82022993)
Location: lib/kobject.c:177
Inline: True
Inline callers:
  - lib/kobject.c:__kobject_del
  - lib/kobject.c:kobject_add_internal
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
In lib/kobject.c (ffffffff820a2a03)
Location: lib/kobject.c:179
Inline: True
Inline callers:
  - lib/kobject.c:__kobject_del
  - lib/kobject.c:kobject_add_internal
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
In lib/kobject.c (ffffffff8217aa83)
Location: lib/kobject.c:186
Inline: True
Inline callers:
  - lib/kobject.c:__kobject_del
  - lib/kobject.c:kobject_add_internal
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
void kobj_kset_leave(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffff800010d8aa48)
Location: lib/kobject.c:201
Inline: False
Direct callers:
  - lib/kobject.c:kobject_del
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffff800010d8aa48-ffff800010d8aaf0: kobj_kset_leave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void kobj_kset_leave(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (c0e8522c)
Location: lib/kobject.c:201
Inline: False
Direct callers:
  - lib/kobject.c:kobject_del
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
c0e8522c-c0e85294: kobj_kset_leave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void kobj_kset_leave(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (c000000000ecbb30)
Location: lib/kobject.c:201
Inline: False
Direct callers:
  - lib/kobject.c:kobject_del
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
c000000000ecbb30-c000000000ecbbf0: kobj_kset_leave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void kobj_kset_leave(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffe0008b3fc8)
Location: lib/kobject.c:201
Inline: False
Direct callers:
  - lib/kobject.c:kobject_del
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffe0008b3fc8-ffffffe0008b404a: kobj_kset_leave (STB_LOCAL)
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
void kobj_kset_leave(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a4f870)
Location: lib/kobject.c:201
Inline: False
Direct callers:
  - lib/kobject.c:kobject_del
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff81a4f870-ffffffff81a4f8c4: kobj_kset_leave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void kobj_kset_leave(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a0c970)
Location: lib/kobject.c:201
Inline: False
Direct callers:
  - lib/kobject.c:kobject_del
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff81a0c970-ffffffff81a0c9c4: kobj_kset_leave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void kobj_kset_leave(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81abbc60)
Location: lib/kobject.c:201
Inline: False
Direct callers:
  - lib/kobject.c:kobject_del
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff81abbc60-ffffffff81abbcb4: kobj_kset_leave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void kobj_kset_leave(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81ac80f0)
Location: lib/kobject.c:201
Inline: False
Direct callers:
  - lib/kobject.c:kobject_del
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff81ac80f0-ffffffff81ac8142: kobj_kset_leave (STB_LOCAL)
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
