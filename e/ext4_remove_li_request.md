# Function: <code>ext4_remove_li_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ext4_remove_li_request(struct ext4_li_request *elr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812ac4a0)
Location: fs/ext4/super.c:2654
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_clear_request_list
  - fs/ext4/super.c:ext4_unregister_li_request
```
**Symbols:**

```
ffffffff812ac4a0-ffffffff812ac4f0: ext4_remove_li_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ext4_remove_li_request(struct ext4_li_request *elr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812e0ac0)
Location: fs/ext4/super.c:2805
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_clear_request_list
  - fs/ext4/super.c:ext4_unregister_li_request
```
**Symbols:**

```
ffffffff812e0ac0-ffffffff812e0b10: ext4_remove_li_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ext4_remove_li_request(struct ext4_li_request *elr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812f6600)
Location: fs/ext4/super.c:2829
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_clear_request_list
  - fs/ext4/super.c:ext4_unregister_li_request
```
**Symbols:**

```
ffffffff812f6600-ffffffff812f6650: ext4_remove_li_request (STB_LOCAL)
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
In fs/ext4/super.c (ffffffff8132bd06)
Location: fs/ext4/super.c:2908
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_clear_request_list
  - fs/ext4/super.c:ext4_unregister_li_request
Direct callers:
  - fs/ext4/super.c:ext4_clear_request_list
  - fs/ext4/super.c:ext4_unregister_li_request
```
**Symbols:**

```
ffffffff8132bc10-ffffffff8132bc56: ext4_remove_li_request.part.185 (STB_LOCAL)
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
In fs/ext4/super.c (ffffffff813501c6)
Location: fs/ext4/super.c:2908
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_clear_request_list
  - fs/ext4/super.c:ext4_unregister_li_request
Direct callers:
  - fs/ext4/super.c:ext4_clear_request_list
  - fs/ext4/super.c:ext4_unregister_li_request
```
**Symbols:**

```
ffffffff813500d0-ffffffff81350116: ext4_remove_li_request.part.186 (STB_LOCAL)
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
In fs/ext4/super.c (ffffffff8137e386)
Location: fs/ext4/super.c:2980
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_clear_request_list
  - fs/ext4/super.c:ext4_unregister_li_request
Direct callers:
  - fs/ext4/super.c:ext4_clear_request_list
  - fs/ext4/super.c:ext4_unregister_li_request
```
**Symbols:**

```
ffffffff8137e290-ffffffff8137e2d6: ext4_remove_li_request.part.114 (STB_LOCAL)
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
In fs/ext4/super.c (ffffffff81396bc6)
Location: fs/ext4/super.c:3044
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_clear_request_list
  - fs/ext4/super.c:ext4_unregister_li_request
Direct callers:
  - fs/ext4/super.c:ext4_clear_request_list
  - fs/ext4/super.c:ext4_unregister_li_request
```
**Symbols:**

```
ffffffff81396b40-ffffffff81396b86: ext4_remove_li_request.part.120 (STB_LOCAL)
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
In fs/ext4/super.c (ffffffff813c0c46)
Location: fs/ext4/super.c:3080
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_clear_request_list
  - fs/ext4/super.c:ext4_unregister_li_request
Direct callers:
  - fs/ext4/super.c:ext4_clear_request_list
  - fs/ext4/super.c:ext4_unregister_li_request
```
**Symbols:**

```
ffffffff813c0bc0-ffffffff813c0c04: ext4_remove_li_request.part.0 (STB_LOCAL)
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
In fs/ext4/super.c (ffffffff813d9f96)
Location: fs/ext4/super.c:3092
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_clear_request_list
  - fs/ext4/super.c:ext4_unregister_li_request
Direct callers:
  - fs/ext4/super.c:ext4_clear_request_list
  - fs/ext4/super.c:ext4_unregister_li_request
```
**Symbols:**

```
ffffffff813d9f10-ffffffff813d9f54: ext4_remove_li_request.part.0 (STB_LOCAL)
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
In fs/ext4/super.c (ffffffff81426efe)
Location: fs/ext4/super.c:3246
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_clear_request_list
  - fs/ext4/super.c:ext4_clear_request_list
  - fs/ext4/super.c:ext4_unregister_li_request
  - fs/ext4/super.c:ext4_unregister_li_request
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
In fs/ext4/super.c (ffffffff8143e5ce)
Location: fs/ext4/super.c:3471
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_clear_request_list
  - fs/ext4/super.c:ext4_clear_request_list
  - fs/ext4/super.c:ext4_unregister_li_request
  - fs/ext4/super.c:ext4_unregister_li_request
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
In fs/ext4/super.c (ffffffff8144441e)
Location: fs/ext4/super.c:3501
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_clear_request_list
  - fs/ext4/super.c:ext4_clear_request_list
  - fs/ext4/super.c:ext4_unregister_li_request
  - fs/ext4/super.c:ext4_unregister_li_request
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
In fs/ext4/super.c (ffffffff8149821e)
Location: fs/ext4/super.c:3323
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_clear_request_list
  - fs/ext4/super.c:ext4_clear_request_list
  - fs/ext4/super.c:ext4_unregister_li_request
  - fs/ext4/super.c:ext4_unregister_li_request
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
In fs/ext4/super.c (ffffffff81522ece)
Location: fs/ext4/super.c:3718
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_clear_request_list
  - fs/ext4/super.c:ext4_clear_request_list
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
In fs/ext4/super.c (ffffffff815c002e)
Location: fs/ext4/super.c:3707
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_clear_request_list
  - fs/ext4/super.c:ext4_clear_request_list
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
In fs/ext4/super.c (ffffffff815f77ce)
Location: fs/ext4/super.c:3758
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_clear_request_list
  - fs/ext4/super.c:ext4_clear_request_list
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
In fs/ext4/super.c (ffffffff8163037e)
Location: fs/ext4/super.c:3764
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_clear_request_list
  - fs/ext4/super.c:ext4_clear_request_list
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
In fs/ext4/super.c (ffff8000104ad5b8)
Location: fs/ext4/super.c:3092
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_clear_request_list
  - fs/ext4/super.c:ext4_unregister_li_request
Direct callers:
  - fs/ext4/super.c:ext4_clear_request_list
  - fs/ext4/super.c:ext4_unregister_li_request
```
**Symbols:**

```
ffff8000104ad520-ffff8000104ad574: ext4_remove_li_request.part.0 (STB_LOCAL)
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
In fs/ext4/super.c (c0676344)
Location: fs/ext4/super.c:3092
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_clear_request_list
  - fs/ext4/super.c:ext4_unregister_li_request
Direct callers:
  - fs/ext4/super.c:ext4_clear_request_list
  - fs/ext4/super.c:ext4_unregister_li_request
```
**Symbols:**

```
c06762bc-c0676304: ext4_remove_li_request.part.0 (STB_LOCAL)
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
In fs/ext4/super.c (c0000000005e6200)
Location: fs/ext4/super.c:3092
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_clear_request_list
  - fs/ext4/super.c:ext4_unregister_li_request
Direct callers:
  - fs/ext4/super.c:ext4_clear_request_list
  - fs/ext4/super.c:ext4_unregister_li_request
```
**Symbols:**

```
c0000000005e6120-c0000000005e61a0: ext4_remove_li_request.part.0 (STB_LOCAL)
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
In fs/ext4/super.c (ffffffe0003309a2)
Location: fs/ext4/super.c:3092
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_clear_request_list
  - fs/ext4/super.c:ext4_unregister_li_request
Direct callers:
  - fs/ext4/super.c:ext4_clear_request_list
  - fs/ext4/super.c:ext4_unregister_li_request
```
**Symbols:**

```
ffffffe00033091c-ffffffe000330960: ext4_remove_li_request.part.0 (STB_LOCAL)
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
In fs/ext4/super.c (ffffffff813d2576)
Location: fs/ext4/super.c:3092
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_clear_request_list
  - fs/ext4/super.c:ext4_unregister_li_request
Direct callers:
  - fs/ext4/super.c:ext4_clear_request_list
  - fs/ext4/super.c:ext4_unregister_li_request
```
**Symbols:**

```
ffffffff813d24f0-ffffffff813d2534: ext4_remove_li_request.part.0 (STB_LOCAL)
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
In fs/ext4/super.c (ffffffff813c2ff6)
Location: fs/ext4/super.c:3092
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_clear_request_list
  - fs/ext4/super.c:ext4_unregister_li_request
Direct callers:
  - fs/ext4/super.c:ext4_clear_request_list
  - fs/ext4/super.c:ext4_unregister_li_request
```
**Symbols:**

```
ffffffff813c2f70-ffffffff813c2fb4: ext4_remove_li_request.part.0 (STB_LOCAL)
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
In fs/ext4/super.c (ffffffff813cfa06)
Location: fs/ext4/super.c:3092
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_clear_request_list
  - fs/ext4/super.c:ext4_unregister_li_request
Direct callers:
  - fs/ext4/super.c:ext4_clear_request_list
  - fs/ext4/super.c:ext4_unregister_li_request
```
**Symbols:**

```
ffffffff813cf980-ffffffff813cf9c4: ext4_remove_li_request.part.0 (STB_LOCAL)
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
In fs/ext4/super.c (ffffffff813e5006)
Location: fs/ext4/super.c:3092
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_clear_request_list
  - fs/ext4/super.c:ext4_unregister_li_request
Direct callers:
  - fs/ext4/super.c:ext4_clear_request_list
  - fs/ext4/super.c:ext4_unregister_li_request
```
**Symbols:**

```
ffffffff813e4f80-ffffffff813e4fc4: ext4_remove_li_request.part.0 (STB_LOCAL)
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
