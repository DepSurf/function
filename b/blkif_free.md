# Function: <code>blkif_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blkif_free(struct blkfront_info *info, int suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81574f40)
Location: drivers/block/xen-blkfront.c:1076
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:blkfront_resume
  - drivers/block/xen-blkfront.c:blkfront_remove
```
**Symbols:**

```
ffffffff81574f40-ffffffff81575502: blkif_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blkif_free(struct blkfront_info *info, int suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff815c8e80)
Location: drivers/block/xen-blkfront.c:1334
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_resume
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:setup_blkring
```
**Symbols:**

```
ffffffff815c8e80-ffffffff815c8f04: blkif_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blkif_free(struct blkfront_info *info, int suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff815f5bd0)
Location: drivers/block/xen-blkfront.c:1333
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_resume
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:setup_blkring
```
**Symbols:**

```
ffffffff815f5bd0-ffffffff815f5c54: blkif_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blkif_free(struct blkfront_info *info, int suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff816098a0)
Location: drivers/block/xen-blkfront.c:1343
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_resume
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:setup_blkring
```
**Symbols:**

```
ffffffff816098a0-ffffffff81609e7f: blkif_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blkif_free(struct blkfront_info *info, int suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81672170)
Location: drivers/block/xen-blkfront.c:1343
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_resume
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:setup_blkring
```
**Symbols:**

```
ffffffff81672170-ffffffff8167274f: blkif_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blkif_free(struct blkfront_info *info, int suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff816adc70)
Location: drivers/block/xen-blkfront.c:1343
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_resume
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:setup_blkring
```
**Symbols:**

```
ffffffff816adc70-ffffffff816ae24c: blkif_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blkif_free(struct blkfront_info *info, int suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff816ceb40)
Location: drivers/block/xen-blkfront.c:1342
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_resume
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:setup_blkring
```
**Symbols:**

```
ffffffff816ceb40-ffffffff816cf11c: blkif_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blkif_free(struct blkfront_info *info, int suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff8170e0f0)
Location: drivers/block/xen-blkfront.c:1342
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_resume
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
**Symbols:**

```
ffffffff8170e0f0-ffffffff8170e174: blkif_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blkif_free(struct blkfront_info *info, int suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff817323f0)
Location: drivers/block/xen-blkfront.c:1342
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_resume
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
**Symbols:**

```
ffffffff817323f0-ffffffff81732474: blkif_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void blkif_free(struct blkfront_info *info, int suspend);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff817efbfa)
Location: drivers/block/xen-blkfront.c:1351
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:setup_blkring
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffffffff817eb7e0-ffffffff817eb868: blkif_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void blkif_free(struct blkfront_info *info, int suspend);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff818044fa)
Location: drivers/block/xen-blkfront.c:1352
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:setup_blkring
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffffffff81800110-ffffffff81800198: blkif_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void blkif_free(struct blkfront_info *info, int suspend);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff817e8c6a)
Location: drivers/block/xen-blkfront.c:1352
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:setup_blkring
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffffffff817e4e40-ffffffff817e4ec1: blkif_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void blkif_free(struct blkfront_info *info, int suspend);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81875031)
Location: drivers/block/xen-blkfront.c:1303
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:setup_blkring
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffffffff81871590-ffffffff81871611: blkif_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void blkif_free(struct blkfront_info *info, int suspend);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff819bc3e1)
Location: drivers/block/xen-blkfront.c:1297
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:setup_blkring
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffffffff819b95d0-ffffffff819b9665: blkif_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void blkif_free(struct blkfront_info *info, int suspend);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81b31a01)
Location: drivers/block/xen-blkfront.c:1300
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:setup_blkring
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffffffff81b2e9f0-ffffffff81b2ea85: blkif_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void blkif_free(struct blkfront_info *info, int suspend);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81b850a1)
Location: drivers/block/xen-blkfront.c:1301
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:setup_blkring
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffffffff81b81e60-ffffffff81b81ef5: blkif_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void blkif_free(struct blkfront_info *info, int suspend);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81bd8fb1)
Location: drivers/block/xen-blkfront.c:1301
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:setup_blkring
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
**Symbols:**

```
ffffffff81bd5d20-ffffffff81bd5db5: blkif_free (STB_LOCAL)
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
void blkif_free(struct blkfront_info *info, int suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffff800010927588)
Location: drivers/block/xen-blkfront.c:1342
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_resume
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
**Symbols:**

```
ffff800010927588-ffff800010927614: blkif_free (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void blkif_free(struct blkfront_info *info, int suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff816f83e0)
Location: drivers/block/xen-blkfront.c:1360
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_resume
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
**Symbols:**

```
ffffffff816f83e0-ffffffff816f841d: blkif_free (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blkif_free(struct blkfront_info *info, int suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff817258b0)
Location: drivers/block/xen-blkfront.c:1342
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_resume
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
**Symbols:**

```
ffffffff817258b0-ffffffff81725934: blkif_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blkif_free(struct blkfront_info *info, int suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81740d00)
Location: drivers/block/xen-blkfront.c:1342
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_resume
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
**Symbols:**

```
ffffffff81740d00-ffffffff81740d84: blkif_free (STB_LOCAL)
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
