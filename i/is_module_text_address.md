# Function: <code>is_module_text_address</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool is_module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8110ab40)
Location: kernel/module.c:4048
Inline: False
Direct callers:
  - kernel/extable.c:__kernel_text_address
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:func_ptr_is_kernel_text
```
**Symbols:**

```
ffffffff8110ab40-ffffffff8110ab56: is_module_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool is_module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81112200)
Location: kernel/module.c:4219
Inline: False
Direct callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:__kernel_text_address
```
**Symbols:**

```
ffffffff81112200-ffffffff81112216: is_module_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool is_module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81119980)
Location: kernel/module.c:4240
Inline: False
Direct callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:__kernel_text_address
```
**Symbols:**

```
ffffffff81119980-ffffffff81119996: is_module_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool is_module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8111b2b0)
Location: kernel/module.c:4286
Inline: False
Direct callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:__kernel_text_address
```
**Symbols:**

```
ffffffff8111b2b0-ffffffff8111b2c6: is_module_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool is_module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81126820)
Location: kernel/module.c:4324
Inline: False
Direct callers:
  - kernel/extable.c:func_ptr_is_kernel_text
```
**Symbols:**

```
ffffffff81126820-ffffffff81126836: is_module_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool is_module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811345b0)
Location: kernel/module.c:4361
Inline: False
Direct callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:kernel_text_address
```
**Symbols:**

```
ffffffff811345b0-ffffffff811345c6: is_module_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool is_module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113fd90)
Location: kernel/module.c:4399
Inline: False
Direct callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:kernel_text_address
```
**Symbols:**

```
ffffffff8113fd90-ffffffff8113fda6: is_module_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool is_module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8114b0e0)
Location: kernel/module.c:4427
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_early
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:kernel_text_address
```
**Symbols:**

```
ffffffff8114b0e0-ffffffff8114b0f6: is_module_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool is_module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81156d60)
Location: kernel/module.c:4494
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_early
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:kernel_text_address
```
**Symbols:**

```
ffffffff81156d60-ffffffff81156d76: is_module_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool is_module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81167910)
Location: kernel/module.c:4502
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_early
  - kernel/extable.c:func_ptr_is_kernel_text
```
**Symbols:**

```
ffffffff81167910-ffffffff8116797b: is_module_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool is_module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81164270)
Location: kernel/module.c:4733
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_early
  - kernel/extable.c:func_ptr_is_kernel_text
```
**Symbols:**

```
ffffffff81164270-ffffffff811642db: is_module_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool is_module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81165040)
Location: kernel/module.c:4672
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_early
  - kernel/extable.c:func_ptr_is_kernel_text
```
**Symbols:**

```
ffffffff81165040-ffffffff811650b4: is_module_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool is_module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8118a750)
Location: kernel/module.c:4695
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_early
  - kernel/extable.c:func_ptr_is_kernel_text
```
**Symbols:**

```
ffffffff8118a750-ffffffff8118a7d5: is_module_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool is_module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff81190460)
Location: kernel/module/main.c:3082
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_early
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/kprobes.c:check_kprobe_address_safe
```
**Symbols:**

```
ffffffff81190460-ffffffff81190499: is_module_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool is_module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811cd800)
Location: kernel/module/main.c:3092
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_early
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/kprobes.c:check_kprobe_address_safe
```
**Symbols:**

```
ffffffff811cd800-ffffffff811cd839: is_module_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool is_module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811e10e0)
Location: kernel/module/main.c:3296
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_early
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/kprobes.c:check_kprobe_address_safe
```
**Symbols:**

```
ffffffff811e10e0-ffffffff811e1167: is_module_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool is_module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811f6e10)
Location: kernel/module/main.c:3307
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_early
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/kprobes.c:check_kprobe_address_safe
```
**Symbols:**

```
ffffffff811f6e10-ffffffff811f6e97: is_module_text_address (STB_GLOBAL)
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
bool is_module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffff8000101c6270)
Location: kernel/module.c:4494
Inline: False
Direct callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:kernel_text_address
```
**Symbols:**

```
ffff8000101c6270-ffff8000101c62a4: is_module_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool is_module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c040d364)
Location: kernel/module.c:4494
Inline: False
Direct callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:kernel_text_address
```
**Symbols:**

```
c040d364-c040d388: is_module_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool is_module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c00000000022e040)
Location: kernel/module.c:4494
Inline: False
Direct callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:kernel_text_address
```
**Symbols:**

```
c00000000022e040-c00000000022e0ac: is_module_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool is_module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffe000146944)
Location: kernel/module.c:4494
Inline: False
Direct callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:kernel_text_address
```
**Symbols:**

```
ffffffe000146944-ffffffe000146972: is_module_text_address (STB_GLOBAL)
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
bool is_module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8114f380)
Location: kernel/module.c:4494
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_early
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:kernel_text_address
```
**Symbols:**

```
ffffffff8114f380-ffffffff8114f396: is_module_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool is_module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81142630)
Location: kernel/module.c:4494
Inline: False
Direct callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:kernel_text_address
```
**Symbols:**

```
ffffffff81142630-ffffffff81142646: is_module_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool is_module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8114d230)
Location: kernel/module.c:4494
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_early
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:kernel_text_address
```
**Symbols:**

```
ffffffff8114d230-ffffffff8114d246: is_module_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool is_module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81159fe0)
Location: kernel/module.c:4494
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_early
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:kernel_text_address
```
**Symbols:**

```
ffffffff81159fe0-ffffffff8115a00d: is_module_text_address (STB_GLOBAL)
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
