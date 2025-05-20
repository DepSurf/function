# Function: <code>ftrace_release_mod</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ftrace_release_mod(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81144da0)
Location: kernel/trace/ftrace.c:4901
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/trace/ftrace.c:ftrace_module_notify_exit
```
**Symbols:**

```
ffffffff81144da0-ffffffff81144e96: ftrace_release_mod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ftrace_release_mod(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8114d500)
Location: kernel/trace/ftrace.c:4951
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:SyS_delete_module
```
**Symbols:**

```
ffffffff8114d500-ffffffff8114d5f6: ftrace_release_mod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ftrace_release_mod(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81157440)
Location: kernel/trace/ftrace.c:5000
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:SyS_delete_module
```
**Symbols:**

```
ffffffff81157440-ffffffff81157536: ftrace_release_mod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ftrace_release_mod(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8115a5b0)
Location: kernel/trace/ftrace.c:5695
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:SyS_delete_module
```
**Symbols:**

```
ffffffff8115a5b0-ffffffff8115a6a5: ftrace_release_mod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ftrace_release_mod(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811670b0)
Location: kernel/trace/ftrace.c:5734
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:SyS_delete_module
```
**Symbols:**

```
ffffffff811670b0-ffffffff81167340: ftrace_release_mod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ftrace_release_mod(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81175dd0)
Location: kernel/trace/ftrace.c:5720
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
**Symbols:**

```
ffffffff81175dd0-ffffffff81176040: ftrace_release_mod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ftrace_release_mod(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81183a10)
Location: kernel/trace/ftrace.c:5680
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
**Symbols:**

```
ffffffff81183a10-ffffffff81183c80: ftrace_release_mod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void ftrace_release_mod(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:5728
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
**Symbols:**

```
ffffffff81192381-ffffffff811923a0: ftrace_release_mod.cold (STB_LOCAL)
ffffffff811907a0-ffffffff811909fd: ftrace_release_mod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ftrace_release_mod(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119c790)
Location: kernel/trace/ftrace.c:5765
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
**Symbols:**

```
ffffffff8119c790-ffffffff8119c9f2: ftrace_release_mod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ftrace_release_mod(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b2970)
Location: kernel/trace/ftrace.c:6256
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
```
**Symbols:**

```
ffffffff811b2970-ffffffff811b2bde: ftrace_release_mod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ftrace_release_mod(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b03e0)
Location: kernel/trace/ftrace.c:6394
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
```
**Symbols:**

```
ffffffff811b03e0-ffffffff811b0649: ftrace_release_mod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ftrace_release_mod(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b0cf0)
Location: kernel/trace/ftrace.c:6399
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
```
**Symbols:**

```
ffffffff811b0cf0-ffffffff811b0f45: ftrace_release_mod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ftrace_release_mod(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:6400
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
```
**Symbols:**

```
ffffffff81cb4755-ffffffff81cb4774: ftrace_release_mod.cold (STB_LOCAL)
ffffffff811dab70-ffffffff811dadd6: ftrace_release_mod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ftrace_release_mod(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:6822
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:do_init_module
```
**Symbols:**

```
ffffffff81e65737-ffffffff81e65756: ftrace_release_mod.cold (STB_LOCAL)
ffffffff81210aa0-ffffffff81210d54: ftrace_release_mod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ftrace_release_mod(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:6938
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:do_init_module
```
**Symbols:**

```
ffffffff8205cf2d-ffffffff8205cf4c: ftrace_release_mod.cold (STB_LOCAL)
ffffffff81259f30-ffffffff8125a1e4: ftrace_release_mod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ftrace_release_mod(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:6753
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:do_init_module
```
**Symbols:**

```
ffffffff820db8c1-ffffffff820db8e0: ftrace_release_mod.cold (STB_LOCAL)
ffffffff81271230-ffffffff812715db: ftrace_release_mod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ftrace_release_mod(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:6757
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:do_init_module
```
**Symbols:**

```
ffffffff821b7621-ffffffff821b7640: ftrace_release_mod.cold (STB_LOCAL)
ffffffff8128b6b0-ffffffff8128ba5b: ftrace_release_mod (STB_GLOBAL)
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
void ftrace_release_mod(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffff800010215598)
Location: kernel/trace/ftrace.c:5765
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:__arm64_sys_delete_module
```
**Symbols:**

```
ffff800010215598-ffff800010215824: ftrace_release_mod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ftrace_release_mod(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c0454300)
Location: kernel/trace/ftrace.c:5765
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:__se_sys_delete_module
```
**Symbols:**

```
c0454300-c0454584: ftrace_release_mod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ftrace_release_mod(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c000000000296e00)
Location: kernel/trace/ftrace.c:5765
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:__se_sys_delete_module
```
**Symbols:**

```
c000000000296e00-c00000000029719c: ftrace_release_mod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ftrace_release_mod(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffe0001752a6)
Location: kernel/trace/ftrace.c:5765
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:__se_sys_delete_module
```
**Symbols:**

```
ffffffe0001752a6-ffffffe00017554e: ftrace_release_mod (STB_GLOBAL)
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
void ftrace_release_mod(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81194db0)
Location: kernel/trace/ftrace.c:5765
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
**Symbols:**

```
ffffffff81194db0-ffffffff81195012: ftrace_release_mod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ftrace_release_mod(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81187ec0)
Location: kernel/trace/ftrace.c:5765
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
**Symbols:**

```
ffffffff81187ec0-ffffffff81188122: ftrace_release_mod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ftrace_release_mod(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81192b80)
Location: kernel/trace/ftrace.c:5765
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
**Symbols:**

```
ffffffff81192b80-ffffffff81192de2: ftrace_release_mod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ftrace_release_mod(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811a0710)
Location: kernel/trace/ftrace.c:5765
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
**Symbols:**

```
ffffffff811a0710-ffffffff811a0972: ftrace_release_mod (STB_GLOBAL)
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
