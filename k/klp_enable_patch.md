# Function: <code>klp_enable_patch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int klp_enable_patch(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff810e9370)
Location: kernel/livepatch/core.c:518
Inline: False
```
**Symbols:**

```
ffffffff810e9370-ffffffff810e93e7: klp_enable_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int klp_enable_patch(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff810effb0)
Location: kernel/livepatch/core.c:582
Inline: False
```
**Symbols:**

```
ffffffff810effb0-ffffffff810f0027: klp_enable_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int klp_enable_patch(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff810f6b60)
Location: kernel/livepatch/core.c:577
Inline: False
```
**Symbols:**

```
ffffffff810f6b60-ffffffff810f6bd7: klp_enable_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int klp_enable_patch(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff810f78e0)
Location: kernel/livepatch/core.c:417
Inline: False
```
**Symbols:**

```
ffffffff810f78e0-ffffffff810f7957: klp_enable_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int klp_enable_patch(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81101b90)
Location: kernel/livepatch/core.c:431
Inline: False
```
**Symbols:**

```
ffffffff81101b90-ffffffff81101c07: klp_enable_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int klp_enable_patch(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81109e90)
Location: kernel/livepatch/core.c:426
Inline: False
```
**Symbols:**

```
ffffffff81109e90-ffffffff81109f07: klp_enable_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int klp_enable_patch(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81115660)
Location: kernel/livepatch/core.c:426
Inline: False
```
**Symbols:**

```
ffffffff81115660-ffffffff811156d7: klp_enable_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int klp_enable_patch(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (ffffffff8111fce5)
Location: kernel/livepatch/core.c:972
Inline: True
```
**Symbols:**

```
ffffffff811205ce-ffffffff811206e8: klp_enable_patch.cold (STB_LOCAL)
ffffffff8111faf0-ffffffff81120235: klp_enable_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int klp_enable_patch(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (ffffffff8112c435)
Location: kernel/livepatch/core.c:972
Inline: True
```
**Symbols:**

```
ffffffff8112ccc6-ffffffff8112cdfd: klp_enable_patch.cold (STB_LOCAL)
ffffffff8112c240-ffffffff8112c956: klp_enable_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int klp_enable_patch(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:1025
Inline: False
```
**Symbols:**

```
ffffffff8113b46a-ffffffff8113b4ae: klp_enable_patch.cold (STB_LOCAL)
ffffffff8113aae0-ffffffff8113aebd: klp_enable_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int klp_enable_patch(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:1025
Inline: False
```
**Symbols:**

```
ffffffff81be3179-ffffffff81be31bd: klp_enable_patch.cold (STB_LOCAL)
ffffffff811355d0-ffffffff811359ad: klp_enable_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int klp_enable_patch(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:1024
Inline: False
```
**Symbols:**

```
ffffffff81bd4f1b-ffffffff81bd508d: klp_enable_patch.cold (STB_LOCAL)
ffffffff81136490-ffffffff811367ee: klp_enable_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int klp_enable_patch(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:1024
Inline: False
```
**Symbols:**

```
ffffffff81cafac4-ffffffff81cafc9b: klp_enable_patch.cold (STB_LOCAL)
ffffffff81159090-ffffffff81159425: klp_enable_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int klp_enable_patch(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:1013
Inline: False
```
**Symbols:**

```
ffffffff81e60756-ffffffff81e6091b: klp_enable_patch.cold (STB_LOCAL)
ffffffff81182610-ffffffff811829a6: klp_enable_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int klp_enable_patch(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:1038
Inline: False
```
**Symbols:**

```
ffffffff8205a52b-ffffffff8205a57e: klp_enable_patch.cold (STB_LOCAL)
ffffffff811bd300-ffffffff811bd805: klp_enable_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int klp_enable_patch(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:1066
Inline: False
```
**Symbols:**

```
ffffffff820d8d30-ffffffff820d8d83: klp_enable_patch.cold (STB_LOCAL)
ffffffff811cfb10-ffffffff811d0010: klp_enable_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int klp_enable_patch(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:1066
Inline: False
```
**Symbols:**

```
ffffffff821b4469-ffffffff821b44bc: klp_enable_patch.cold (STB_LOCAL)
ffffffff811e4760-ffffffff811e4c60: klp_enable_patch (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int klp_enable_patch(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (c0000000001f03e0)
Location: kernel/livepatch/core.c:972
Inline: True
```
**Symbols:**

```
c0000000001f03e0-c0000000001f10bc: klp_enable_patch (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int klp_enable_patch(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81124a15)
Location: kernel/livepatch/core.c:972
Inline: True
```
**Symbols:**

```
ffffffff811252a6-ffffffff811253dd: klp_enable_patch.cold (STB_LOCAL)
ffffffff81124820-ffffffff81124f36: klp_enable_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int klp_enable_patch(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81117475)
Location: kernel/livepatch/core.c:972
Inline: True
```
**Symbols:**

```
ffffffff81117d06-ffffffff81117e3d: klp_enable_patch.cold (STB_LOCAL)
ffffffff81117280-ffffffff81117996: klp_enable_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int klp_enable_patch(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81122905)
Location: kernel/livepatch/core.c:972
Inline: True
```
**Symbols:**

```
ffffffff81123196-ffffffff811232cd: klp_enable_patch.cold (STB_LOCAL)
ffffffff81122710-ffffffff81122e26: klp_enable_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int klp_enable_patch(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (ffffffff8112ef15)
Location: kernel/livepatch/core.c:972
Inline: True
```
**Symbols:**

```
ffffffff8112f7a6-ffffffff8112f8dd: klp_enable_patch.cold (STB_LOCAL)
ffffffff8112ed20-ffffffff8112f436: klp_enable_patch (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
