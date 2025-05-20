# Function: <code>perf_trace_module_refcnt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void perf_trace_module_refcnt(void *__data, struct module *mod, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81104940)
Location: include/trace/events/module.h:69
Inline: False
```
**Symbols:**

```
ffffffff81104940-ffffffff81104ac6: perf_trace_module_refcnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void perf_trace_module_refcnt(void *__data, struct module *mod, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8110c0c0)
Location: include/trace/events/module.h:69
Inline: False
```
**Symbols:**

```
ffffffff8110c0c0-ffffffff8110c232: perf_trace_module_refcnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void perf_trace_module_refcnt(void *__data, struct module *mod, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81113b20)
Location: include/trace/events/module.h:69
Inline: False
```
**Symbols:**

```
ffffffff81113b20-ffffffff81113c90: perf_trace_module_refcnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void perf_trace_module_refcnt(void *__data, struct module *mod, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811170c0)
Location: include/trace/events/module.h:69
Inline: False
```
**Symbols:**

```
ffffffff811170c0-ffffffff81117227: perf_trace_module_refcnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void perf_trace_module_refcnt(void *__data, struct module *mod, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811226c0)
Location: include/trace/events/module.h:70
Inline: False
```
**Symbols:**

```
ffffffff811226c0-ffffffff81122820: perf_trace_module_refcnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void perf_trace_module_refcnt(void *__data, struct module *mod, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811301a0)
Location: include/trace/events/module.h:70
Inline: False
```
**Symbols:**

```
ffffffff811301a0-ffffffff811302f7: perf_trace_module_refcnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void perf_trace_module_refcnt(void *__data, struct module *mod, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113ba50)
Location: include/trace/events/module.h:70
Inline: False
```
**Symbols:**

```
ffffffff8113ba50-ffffffff8113bba7: perf_trace_module_refcnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void perf_trace_module_refcnt(void *__data, struct module *mod, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81147070)
Location: include/trace/events/module.h:70
Inline: False
```
**Symbols:**

```
ffffffff81147070-ffffffff811471bc: perf_trace_module_refcnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void perf_trace_module_refcnt(void *__data, struct module *mod, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81152e90)
Location: include/trace/events/module.h:70
Inline: False
```
**Symbols:**

```
ffffffff81152e90-ffffffff81152fdc: perf_trace_module_refcnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_trace_module_refcnt(void *__data, struct module *mod, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81164390)
Location: include/trace/events/module.h:70
Inline: False
```
**Symbols:**

```
ffffffff81164390-ffffffff811644e3: perf_trace_module_refcnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void perf_trace_module_refcnt(void *__data, struct module *mod, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: include/trace/events/module.h:70
Inline: False
```
**Symbols:**

```
ffffffff81160210-ffffffff8116040a: perf_trace_module_refcnt (STB_LOCAL)
ffffffff81be40a3-ffffffff81be40bb: perf_trace_module_refcnt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void perf_trace_module_refcnt(void *__data, struct module *mod, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: include/trace/events/module.h:70
Inline: False
```
**Symbols:**

```
ffffffff811610e0-ffffffff811612e5: perf_trace_module_refcnt (STB_LOCAL)
ffffffff81bd5fb1-ffffffff81bd5fc9: perf_trace_module_refcnt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void perf_trace_module_refcnt(void *__data, struct module *mod, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: include/trace/events/module.h:70
Inline: False
```
**Symbols:**

```
ffffffff811862b0-ffffffff811864b5: perf_trace_module_refcnt (STB_LOCAL)
ffffffff81cb26dc-ffffffff81cb26f4: perf_trace_module_refcnt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void perf_trace_module_refcnt(void *__data, struct module *mod, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module/main.c (0)
Location: include/trace/events/module.h:70
Inline: False
```
**Symbols:**

```
ffffffff8118bab0-ffffffff8118bcd0: perf_trace_module_refcnt (STB_LOCAL)
ffffffff81e615d7-ffffffff81e615ef: perf_trace_module_refcnt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_trace_module_refcnt(void *__data, struct module *mod, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811c8190)
Location: include/trace/events/module.h:70
Inline: False
```
**Symbols:**

```
ffffffff811c8190-ffffffff811c83c9: perf_trace_module_refcnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_trace_module_refcnt(void *__data, struct module *mod, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811db1f0)
Location: include/trace/events/module.h:70
Inline: False
```
**Symbols:**

```
ffffffff811db1f0-ffffffff811db459: perf_trace_module_refcnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_trace_module_refcnt(void *__data, struct module *mod, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811f0ea0)
Location: include/trace/events/module.h:70
Inline: False
```
**Symbols:**

```
ffffffff811f0ea0-ffffffff811f1109: perf_trace_module_refcnt (STB_LOCAL)
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
void perf_trace_module_refcnt(void *__data, struct module *mod, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffff8000101c2640)
Location: include/trace/events/module.h:70
Inline: False
```
**Symbols:**

```
ffff8000101c2640-ffff8000101c277c: perf_trace_module_refcnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_trace_module_refcnt(void *__data, struct module *mod, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c0409144)
Location: include/trace/events/module.h:70
Inline: False
```
**Symbols:**

```
c0409144-c040928c: perf_trace_module_refcnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_trace_module_refcnt(void *__data, struct module *mod, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c000000000228540)
Location: include/trace/events/module.h:70
Inline: False
```
**Symbols:**

```
c000000000228540-c000000000228708: perf_trace_module_refcnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void perf_trace_module_refcnt(void *__data, struct module *mod, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffe00014134c)
Location: include/trace/events/module.h:70
Inline: False
```
**Symbols:**

```
ffffffe00014134c-ffffffe000141436: perf_trace_module_refcnt (STB_LOCAL)
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
void perf_trace_module_refcnt(void *__data, struct module *mod, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8114b4b0)
Location: include/trace/events/module.h:70
Inline: False
```
**Symbols:**

```
ffffffff8114b4b0-ffffffff8114b5fc: perf_trace_module_refcnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void perf_trace_module_refcnt(void *__data, struct module *mod, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113e760)
Location: include/trace/events/module.h:70
Inline: False
```
**Symbols:**

```
ffffffff8113e760-ffffffff8113e8ac: perf_trace_module_refcnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void perf_trace_module_refcnt(void *__data, struct module *mod, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81149360)
Location: include/trace/events/module.h:70
Inline: False
```
**Symbols:**

```
ffffffff81149360-ffffffff811494ac: perf_trace_module_refcnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void perf_trace_module_refcnt(void *__data, struct module *mod, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81156020)
Location: include/trace/events/module.h:70
Inline: False
```
**Symbols:**

```
ffffffff81156020-ffffffff8115616c: perf_trace_module_refcnt (STB_LOCAL)
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
