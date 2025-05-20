# Function: <code>module_arch_cleanup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void module_arch_cleanup(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff81060cd0)
Location: arch/x86/kernel/module.c:253
Inline: False
```
**Symbols:**

```
ffffffff81060cd0-ffffffff81060ce0: module_arch_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void module_arch_cleanup(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff81060af0)
Location: arch/x86/kernel/module.c:254
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff81060af0-ffffffff81060b00: module_arch_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void module_arch_cleanup(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff81063b90)
Location: arch/x86/kernel/module.c:254
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff81063b90-ffffffff81063ba0: module_arch_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void module_arch_cleanup(struct module *mod);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff81062ad0)
Location: arch/x86/kernel/module.c:254
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff81062ad0-ffffffff81062ae0: module_arch_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void module_arch_cleanup(struct module *mod);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff81066c60)
Location: arch/x86/kernel/module.c:277
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff81066c60-ffffffff81066c70: module_arch_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void module_arch_cleanup(struct module *mod);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff810697d0)
Location: arch/x86/kernel/module.c:277
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff810697d0-ffffffff810697e0: module_arch_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void module_arch_cleanup(struct module *mod);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff8106f580)
Location: arch/x86/kernel/module.c:283
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff8106f580-ffffffff8106f590: module_arch_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void module_arch_cleanup(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff81073660)
Location: arch/x86/kernel/module.c:271
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff81073660-ffffffff81073670: module_arch_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void module_arch_cleanup(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff81074620)
Location: arch/x86/kernel/module.c:271
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff81074620-ffffffff81074630: module_arch_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void module_arch_cleanup(struct module *mod);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff8107b860)
Location: arch/x86/kernel/module.c:299
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff8107b860-ffffffff8107b870: module_arch_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void module_arch_cleanup(struct module *mod);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff8107b7c0)
Location: arch/x86/kernel/module.c:300
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff8107b7c0-ffffffff8107b7d0: module_arch_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void module_arch_cleanup(struct module *mod);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff8107c9e0)
Location: arch/x86/kernel/module.c:300
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff8107c9e0-ffffffff8107c9f0: module_arch_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void module_arch_cleanup(struct module *mod);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff8108ab00)
Location: arch/x86/kernel/module.c:304
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff8108ab00-ffffffff8108ab10: module_arch_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void module_arch_cleanup(struct module *mod);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff8109b1c0)
Location: arch/x86/kernel/module.c:323
Inline: True
Direct callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:free_module
```
**Symbols:**

```
ffffffff8109b1c0-ffffffff8109b1d6: module_arch_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void module_arch_cleanup(struct module *mod);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff810b1da0)
Location: arch/x86/kernel/module.c:356
Inline: True
Direct callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:free_module
```
**Symbols:**

```
ffffffff810b1da0-ffffffff810b1db6: module_arch_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void module_arch_cleanup(struct module *mod);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff810b4eb0)
Location: arch/x86/kernel/module.c:379
Inline: True
Direct callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:free_module
```
**Symbols:**

```
ffffffff810b4eb0-ffffffff810b4ec6: module_arch_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void module_arch_cleanup(struct module *mod);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff810bc2f0)
Location: arch/x86/kernel/module.c:369
Inline: True
Direct callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:free_module
```
**Symbols:**

```
ffffffff810bc2f0-ffffffff810bc306: module_arch_cleanup (STB_GLOBAL)
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
void module_arch_cleanup(struct module *mod);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffff8000101c30d8)
Location: kernel/module.c:2181
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffff8000101c30d8-ffff8000101c30f0: module_arch_cleanup (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void module_arch_cleanup(struct module *mod);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/module.c (c0310ca0)
Location: arch/arm/kernel/module.c:407
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
c0310ca0-c0310cb8: module_arch_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void module_arch_cleanup(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c0000000002296b0)
Location: kernel/module.c:2181
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
c0000000002296b0-c0000000002296bc: module_arch_cleanup (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void module_arch_cleanup(struct module *mod);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffe00014407a)
Location: kernel/module.c:2181
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffe00014407a-ffffffe000144094: module_arch_cleanup (STB_WEAK)
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
void module_arch_cleanup(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff81073620)
Location: arch/x86/kernel/module.c:271
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff81073620-ffffffff81073630: module_arch_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void module_arch_cleanup(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff810636a0)
Location: arch/x86/kernel/module.c:271
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff810636a0-ffffffff810636b0: module_arch_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void module_arch_cleanup(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff810735d0)
Location: arch/x86/kernel/module.c:271
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff810735d0-ffffffff810735e0: module_arch_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void module_arch_cleanup(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff81075630)
Location: arch/x86/kernel/module.c:271
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff81075630-ffffffff81075640: module_arch_cleanup (STB_GLOBAL)
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
