# Function: <code>add_kallsyms</code>

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
In kernel/module.c (ffffffff811098b5)
Location: kernel/module.c:2501
Inline: True
Inline callers:
  - kernel/module.c:load_module
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
In kernel/module.c (ffffffff81110909)
Location: kernel/module.c:2624
Inline: True
Inline callers:
  - kernel/module.c:load_module
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
In kernel/module.c (ffffffff81118129)
Location: kernel/module.c:2636
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811199db)
Location: kernel/module.c:2663
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81124f83)
Location: kernel/module.c:2671
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811331cb)
Location: kernel/module.c:2666
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113ea9f)
Location: kernel/module.c:2672
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811493ae)
Location: kernel/module.c:2676
Inline: True
Inline callers:
  - kernel/module.c:post_relocation
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8115502e)
Location: kernel/module.c:2746
Inline: True
Inline callers:
  - kernel/module.c:post_relocation
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void add_kallsyms(struct module *mod, const struct load_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81162370)
Location: kernel/module.c:2740
Inline: False
Direct callers:
  - kernel/module.c:post_relocation
```
**Symbols:**

```
ffffffff81162370-ffffffff8116262e: add_kallsyms (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void add_kallsyms(struct module *mod, const struct load_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8115e3d0)
Location: kernel/module.c:2827
Inline: False
Direct callers:
  - kernel/module.c:post_relocation
```
**Symbols:**

```
ffffffff8115e3d0-ffffffff8115e68e: add_kallsyms (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void add_kallsyms(struct module *mod, const struct load_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8115f3f0)
Location: kernel/module.c:2751
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff8115f3f0-ffffffff8115f6d3: add_kallsyms (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void add_kallsyms(struct module *mod, const struct load_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:2753
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff811847b0-ffffffff81184aa0: add_kallsyms (STB_LOCAL)
ffffffff81cb24d7-ffffffff81cb2502: add_kallsyms.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void add_kallsyms(struct module *mod, const struct load_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module/kallsyms.c (0)
Location: kernel/module/kallsyms.c:166
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
```
**Symbols:**

```
ffffffff81e61c10-ffffffff81e61c43: add_kallsyms.cold (STB_LOCAL)
ffffffff81191370-ffffffff811916e2: add_kallsyms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void add_kallsyms(struct module *mod, const struct load_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module/kallsyms.c (0)
Location: kernel/module/kallsyms.c:166
Inline: False
Direct callers:
  - kernel/module/main.c:post_relocation
```
**Symbols:**

```
ffffffff8205ac47-ffffffff8205ac7a: add_kallsyms.cold (STB_LOCAL)
ffffffff811ce9c0-ffffffff811ced48: add_kallsyms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void add_kallsyms(struct module *mod, const struct load_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module/kallsyms.c (0)
Location: kernel/module/kallsyms.c:170
Inline: False
Direct callers:
  - kernel/module/main.c:post_relocation
```
**Symbols:**

```
ffffffff820d94e9-ffffffff820d9514: add_kallsyms.cold (STB_LOCAL)
ffffffff811e2c10-ffffffff811e2f56: add_kallsyms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void add_kallsyms(struct module *mod, const struct load_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module/kallsyms.c (0)
Location: kernel/module/kallsyms.c:170
Inline: False
Direct callers:
  - kernel/module/main.c:post_relocation
```
**Symbols:**

```
ffffffff821b4d6a-ffffffff821b4d95: add_kallsyms.cold (STB_LOCAL)
ffffffff811f8970-ffffffff811f8cb6: add_kallsyms (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffff8000101c445c)
Location: kernel/module.c:2746
Inline: True
Inline callers:
  - kernel/module.c:post_relocation
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (c040b6cc)
Location: kernel/module.c:2746
Inline: True
Inline callers:
  - kernel/module.c:post_relocation
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (c00000000022b5a8)
Location: kernel/module.c:2746
Inline: True
Inline callers:
  - kernel/module.c:post_relocation
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffe000145b30)
Location: kernel/module.c:2746
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8114d64e)
Location: kernel/module.c:2746
Inline: True
Inline callers:
  - kernel/module.c:post_relocation
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811408fe)
Location: kernel/module.c:2746
Inline: True
Inline callers:
  - kernel/module.c:post_relocation
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8114b4fe)
Location: kernel/module.c:2746
Inline: True
Inline callers:
  - kernel/module.c:post_relocation
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811581ee)
Location: kernel/module.c:2746
Inline: True
Inline callers:
  - kernel/module.c:post_relocation
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
