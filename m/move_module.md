# Function: <code>move_module</code>

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
In kernel/module.c (ffffffff81108256)
Location: kernel/module.c:2969
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
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
In kernel/module.c (ffffffff8110f8cc)
Location: kernel/module.c:3068
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
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
In kernel/module.c (ffffffff811171a3)
Location: kernel/module.c:3083
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
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
In kernel/module.c (ffffffff81118831)
Location: kernel/module.c:3126
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
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
In kernel/module.c (ffffffff81123da4)
Location: kernel/module.c:3146
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
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
In kernel/module.c (ffffffff8113210d)
Location: kernel/module.c:3173
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
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
In kernel/module.c (ffffffff8113d6f2)
Location: kernel/module.c:3172
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
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
In kernel/module.c (ffffffff81149008)
Location: kernel/module.c:3185
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
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
In kernel/module.c (ffffffff81154cbb)
Location: kernel/module.c:3252
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int move_module(struct module *mod, struct load_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81166180)
Location: kernel/module.c:3262
Inline: False
Direct callers:
  - kernel/module.c:layout_and_allocate
```
**Symbols:**

```
ffffffff81166180-ffffffff811662f8: move_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int move_module(struct module *mod, struct load_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811628b0)
Location: kernel/module.c:3449
Inline: False
Direct callers:
  - kernel/module.c:layout_and_allocate
```
**Symbols:**

```
ffffffff811628b0-ffffffff81162a28: move_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int move_module(struct module *mod, struct load_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81163360)
Location: kernel/module.c:3353
Inline: False
Direct callers:
  - kernel/module.c:layout_and_allocate
```
**Symbols:**

```
ffffffff81163360-ffffffff811634d2: move_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int move_module(struct module *mod, struct load_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811888c0)
Location: kernel/module.c:3380
Inline: False
Direct callers:
  - kernel/module.c:layout_and_allocate
```
**Symbols:**

```
ffffffff811888c0-ffffffff81188a2c: move_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int move_module(struct module *mod, struct load_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff8118e700)
Location: kernel/module/main.c:2102
Inline: False
Direct callers:
  - kernel/module/main.c:layout_and_allocate
```
**Symbols:**

```
ffffffff8118e700-ffffffff8118e86e: move_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int move_module(struct module *mod, struct load_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811cb0f0)
Location: kernel/module/main.c:2120
Inline: False
Direct callers:
  - kernel/module/main.c:layout_and_allocate
```
**Symbols:**

```
ffffffff811cb0f0-ffffffff811cb254: move_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int move_module(struct module *mod, struct load_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811de510)
Location: kernel/module/main.c:2214
Inline: False
```
**Symbols:**

```
ffffffff811de510-ffffffff811de802: move_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int move_module(struct module *mod, struct load_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811f4240)
Location: kernel/module/main.c:2225
Inline: False
```
**Symbols:**

```
ffffffff811f4240-ffffffff811f4532: move_module (STB_LOCAL)
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
In kernel/module.c (ffff8000101c3ef8)
Location: kernel/module.c:3252
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
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
In kernel/module.c (c040b1cc)
Location: kernel/module.c:3252
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
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
In kernel/module.c (c00000000022a9cc)
Location: kernel/module.c:3252
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
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
In kernel/module.c (ffffffe000144c42)
Location: kernel/module.c:3252
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
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
In kernel/module.c (ffffffff8114d2db)
Location: kernel/module.c:3252
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
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
In kernel/module.c (ffffffff8114058b)
Location: kernel/module.c:3252
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
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
In kernel/module.c (ffffffff8114b18b)
Location: kernel/module.c:3252
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
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
In kernel/module.c (ffffffff81157e7b)
Location: kernel/module.c:3252
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
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
