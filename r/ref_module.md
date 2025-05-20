# Function: <code>ref_module</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int ref_module(struct module *a, struct module *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811061a0)
Location: kernel/module.c:828
Inline: True
```
**Symbols:**

```
ffffffff811061a0-ffffffff81106337: ref_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int ref_module(struct module *a, struct module *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8110daf0)
Location: kernel/module.c:830
Inline: True
```
**Symbols:**

```
ffffffff8110daf0-ffffffff8110dc77: ref_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int ref_module(struct module *a, struct module *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81115400)
Location: kernel/module.c:833
Inline: True
```
**Symbols:**

```
ffffffff81115400-ffffffff81115587: ref_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ref_module(struct module *a, struct module *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81115f50)
Location: kernel/module.c:853
Inline: True
```
**Symbols:**

```
ffffffff81115f50-ffffffff811160cf: ref_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ref_module(struct module *a, struct module *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811214e0)
Location: kernel/module.c:861
Inline: True
```
**Symbols:**

```
ffffffff811214e0-ffffffff8112164f: ref_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int ref_module(struct module *a, struct module *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8112efc0)
Location: kernel/module.c:860
Inline: True
```
**Symbols:**

```
ffffffff8112efc0-ffffffff8112f13b: ref_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int ref_module(struct module *a, struct module *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113a950)
Location: kernel/module.c:861
Inline: True
```
**Symbols:**

```
ffffffff8113a950-ffffffff8113aacb: ref_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int ref_module(struct module *a, struct module *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81146270)
Location: kernel/module.c:857
Inline: True
```
**Symbols:**

```
ffffffff81146270-ffffffff811463eb: ref_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int ref_module(struct module *a, struct module *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81151e00)
Location: kernel/module.c:869
Inline: True
Direct callers:
  - kernel/module.c:resolve_symbol
```
**Symbols:**

```
ffffffff81151e00-ffffffff81151f7b: ref_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int ref_module(struct module *a, struct module *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81163770)
Location: kernel/module.c:872
Inline: True
Direct callers:
  - kernel/module.c:resolve_symbol
```
**Symbols:**

```
ffffffff81163770-ffffffff81163889: ref_module (STB_GLOBAL)
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
In kernel/module.c (ffffffff8115fa99)
Location: kernel/module.c:907
Inline: True
Inline callers:
  - kernel/module.c:resolve_symbol
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ref_module(struct module *a, struct module *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81160270)
Location: kernel/module.c:812
Inline: False
Direct callers:
  - kernel/module.c:resolve_symbol
```
**Symbols:**

```
ffffffff81160270-ffffffff811603e7: ref_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ref_module(struct module *a, struct module *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81185410)
Location: kernel/module.c:813
Inline: False
Direct callers:
  - kernel/module.c:resolve_symbol
```
**Symbols:**

```
ffffffff81185410-ffffffff81185587: ref_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ref_module(struct module *a, struct module *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff8118bee0)
Location: kernel/module/main.c:593
Inline: False
Direct callers:
  - kernel/module/main.c:resolve_symbol
```
**Symbols:**

```
ffffffff8118bee0-ffffffff8118c067: ref_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ref_module(struct module *a, struct module *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811c8620)
Location: kernel/module/main.c:594
Inline: False
Direct callers:
  - kernel/module/main.c:resolve_symbol
```
**Symbols:**

```
ffffffff811c8620-ffffffff811c87a1: ref_module (STB_LOCAL)
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
In kernel/module/main.c (ffffffff811dcd54)
Location: kernel/module/main.c:599
Inline: True
Inline callers:
  - kernel/module/main.c:resolve_symbol
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ref_module(struct module *a, struct module *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811f1240)
Location: kernel/module/main.c:599
Inline: False
Direct callers:
  - kernel/module/main.c:resolve_symbol
```
**Symbols:**

```
ffffffff811f1240-ffffffff811f13c7: ref_module (STB_LOCAL)
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
int ref_module(struct module *a, struct module *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffff8000101c2890)
Location: kernel/module.c:869
Inline: True
Direct callers:
  - kernel/module.c:resolve_symbol
```
**Symbols:**

```
ffff8000101c2890-ffff8000101c2a38: ref_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int ref_module(struct module *a, struct module *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (c0408bb0)
Location: kernel/module.c:869
Inline: True
Direct callers:
  - kernel/module.c:resolve_symbol
```
**Symbols:**

```
c0408bb0-c0408d34: ref_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int ref_module(struct module *a, struct module *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (c000000000226f60)
Location: kernel/module.c:869
Inline: True
Direct callers:
  - kernel/module.c:resolve_symbol
```
**Symbols:**

```
c000000000226f60-c000000000227180: ref_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int ref_module(struct module *a, struct module *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffe000142f90)
Location: kernel/module.c:869
Inline: True
Direct callers:
  - kernel/module.c:resolve_symbol
```
**Symbols:**

```
ffffffe000142f90-ffffffe0001430f2: ref_module (STB_GLOBAL)
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
int ref_module(struct module *a, struct module *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8114a420)
Location: kernel/module.c:869
Inline: True
Direct callers:
  - kernel/module.c:resolve_symbol
```
**Symbols:**

```
ffffffff8114a420-ffffffff8114a59b: ref_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int ref_module(struct module *a, struct module *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113d6d0)
Location: kernel/module.c:869
Inline: True
Direct callers:
  - kernel/module.c:resolve_symbol
```
**Symbols:**

```
ffffffff8113d6d0-ffffffff8113d84b: ref_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int ref_module(struct module *a, struct module *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811482d0)
Location: kernel/module.c:869
Inline: True
Direct callers:
  - kernel/module.c:resolve_symbol
```
**Symbols:**

```
ffffffff811482d0-ffffffff8114844b: ref_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int ref_module(struct module *a, struct module *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81154f20)
Location: kernel/module.c:869
Inline: True
Direct callers:
  - kernel/module.c:resolve_symbol
```
**Symbols:**

```
ffffffff81154f20-ffffffff8115509b: ref_module (STB_GLOBAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
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
