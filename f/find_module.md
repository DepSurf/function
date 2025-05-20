# Function: <code>find_module</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct module *find_module(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811050b0)
Location: kernel/module.c:604
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/module.c:SyS_delete_module
```
**Symbols:**

```
ffffffff811050b0-ffffffff811050d2: find_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct module *find_module(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8110c990)
Location: kernel/module.c:606
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/module.c:SyS_delete_module
```
**Symbols:**

```
ffffffff8110c990-ffffffff8110c9b2: find_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct module *find_module(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811143d0)
Location: kernel/module.c:609
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/module.c:SyS_delete_module
```
**Symbols:**

```
ffffffff811143d0-ffffffff811143f2: find_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct module *find_module(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811151d0)
Location: kernel/module.c:613
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/module.c:SyS_delete_module
```
**Symbols:**

```
ffffffff811151d0-ffffffff811151f2: find_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct module *find_module(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81120770)
Location: kernel/module.c:623
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/module.c:SyS_delete_module
```
**Symbols:**

```
ffffffff81120770-ffffffff81120792: find_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct module *find_module(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8112e1f0)
Location: kernel/module.c:622
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
**Symbols:**

```
ffffffff8112e1f0-ffffffff8112e212: find_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct module *find_module(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81139af0)
Location: kernel/module.c:623
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
**Symbols:**

```
ffffffff81139af0-ffffffff81139b12: find_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct module *find_module(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811451b0)
Location: kernel/module.c:619
Inline: False
Direct callers:
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
**Symbols:**

```
ffffffff811451b0-ffffffff811451d4: find_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct module *find_module(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81150cc0)
Location: kernel/module.c:631
Inline: False
Direct callers:
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
**Symbols:**

```
ffffffff81150cc0-ffffffff81150ce4: find_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct module *find_module(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81161210)
Location: kernel/module.c:634
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_init_object
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
```
**Symbols:**

```
ffffffff81161210-ffffffff81161236: find_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct module *find_module(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8115d0a0)
Location: kernel/module.c:670
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_init_object
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
```
**Symbols:**

```
ffffffff8115d0a0-ffffffff8115d0c6: find_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct module *find_module(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81162740)
Location: kernel/module.c:577
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_init_object
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
```
**Symbols:**

```
ffffffff81162740-ffffffff81162766: find_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct module *find_module(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81187c50)
Location: kernel/module.c:578
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_init_object
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
```
**Symbols:**

```
ffffffff81187c50-ffffffff81187c76: find_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct module *find_module(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff8118dc30)
Location: kernel/module/main.c:358
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_init_object
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
```
**Symbols:**

```
ffffffff8118dc30-ffffffff8118dc5f: find_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct module *find_module(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811ca790)
Location: kernel/module/main.c:356
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_init_object
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
```
**Symbols:**

```
ffffffff811ca790-ffffffff811ca7bf: find_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct module *find_module(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811dd9e0)
Location: kernel/module/main.c:363
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_init_object
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
```
**Symbols:**

```
ffffffff811dd9e0-ffffffff811dda0f: find_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct module *find_module(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811f36e0)
Location: kernel/module/main.c:363
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_init_object
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
```
**Symbols:**

```
ffffffff811f36e0-ffffffff811f370f: find_module (STB_GLOBAL)
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
struct module *find_module(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffff8000101bfaf0)
Location: kernel/module.c:631
Inline: False
Direct callers:
  - kernel/module.c:__arm64_sys_delete_module
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
**Symbols:**

```
ffff8000101bfaf0-ffff8000101bfb2c: find_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct module *find_module(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c0407288)
Location: kernel/module.c:631
Inline: False
Direct callers:
  - kernel/module.c:__se_sys_delete_module
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
**Symbols:**

```
c0407288-c04072b8: find_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct module *find_module(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c0000000002254c0)
Location: kernel/module.c:631
Inline: False
Direct callers:
  - kernel/module.c:__se_sys_delete_module
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
**Symbols:**

```
c0000000002254c0-c00000000022550c: find_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct module *find_module(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffe000141f76)
Location: kernel/module.c:631
Inline: False
Direct callers:
  - kernel/module.c:__se_sys_delete_module
```
**Symbols:**

```
ffffffe000141f76-ffffffe000141fae: find_module (STB_GLOBAL)
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
struct module *find_module(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811492e0)
Location: kernel/module.c:631
Inline: False
Direct callers:
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
**Symbols:**

```
ffffffff811492e0-ffffffff81149304: find_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct module *find_module(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113c590)
Location: kernel/module.c:631
Inline: False
Direct callers:
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
**Symbols:**

```
ffffffff8113c590-ffffffff8113c5b4: find_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct module *find_module(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81147190)
Location: kernel/module.c:631
Inline: False
Direct callers:
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
**Symbols:**

```
ffffffff81147190-ffffffff811471b4: find_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct module *find_module(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81153da0)
Location: kernel/module.c:631
Inline: False
Direct callers:
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
**Symbols:**

```
ffffffff81153da0-ffffffff81153dc4: find_module (STB_GLOBAL)
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
