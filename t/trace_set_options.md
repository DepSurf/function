# Function: <code>trace_set_options</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int trace_set_options(struct trace_array *tr, char *option);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81151e50)
Location: kernel/trace/trace.c:3583
Inline: False
Direct callers:
  - kernel/trace/trace.c:apply_trace_boot_options
  - kernel/trace/trace.c:tracing_trace_options_write
```
**Symbols:**

```
ffffffff81151e50-ffffffff81151f9d: trace_set_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int trace_set_options(struct trace_array *tr, char *option);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8115aee0)
Location: kernel/trace/trace.c:3923
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_trace_options_write
  - kernel/trace/trace.c:apply_trace_boot_options
```
**Symbols:**

```
ffffffff8115aee0-ffffffff8115b032: trace_set_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int trace_set_options(struct trace_array *tr, char *option);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811656f0)
Location: kernel/trace/trace.c:4147
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_trace_options_write
  - kernel/trace/trace.c:apply_trace_boot_options
```
**Symbols:**

```
ffffffff811656f0-ffffffff81165842: trace_set_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int trace_set_options(struct trace_array *tr, char *option);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81168cc0)
Location: kernel/trace/trace.c:4392
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_trace_options_write
  - kernel/trace/trace.c:apply_trace_boot_options
```
**Symbols:**

```
ffffffff81168cc0-ffffffff81168e10: trace_set_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int trace_set_options(struct trace_array *tr, char *option);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81175c60)
Location: kernel/trace/trace.c:4396
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_trace_options_write
  - kernel/trace/trace.c:apply_trace_boot_options
```
**Symbols:**

```
ffffffff81175c60-ffffffff81175db0: trace_set_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int trace_set_options(struct trace_array *tr, char *option);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81184be0)
Location: kernel/trace/trace.c:4403
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_trace_options_write
  - kernel/trace/trace.c:apply_trace_boot_options
```
**Symbols:**

```
ffffffff81184be0-ffffffff81184d2b: trace_set_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int trace_set_options(struct trace_array *tr, char *option);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81192510)
Location: kernel/trace/trace.c:4407
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_trace_options_write
  - kernel/trace/trace.c:apply_trace_boot_options
```
**Symbols:**

```
ffffffff81192510-ffffffff8119265f: trace_set_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int trace_set_options(struct trace_array *tr, char *option);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119fe80)
Location: kernel/trace/trace.c:4612
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_trace_options_write
  - kernel/trace/trace.c:apply_trace_boot_options
```
**Symbols:**

```
ffffffff8119fe80-ffffffff8119ffb9: trace_set_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int trace_set_options(struct trace_array *tr, char *option);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811ab870)
Location: kernel/trace/trace.c:4656
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_trace_options_write
  - kernel/trace/trace.c:apply_trace_boot_options
```
**Symbols:**

```
ffffffff811ab870-ffffffff811ab9c1: trace_set_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int trace_set_options(struct trace_array *tr, char *option);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c40e0)
Location: kernel/trace/trace.c:4859
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_trace_options_write
  - kernel/trace/trace.c:apply_trace_boot_options
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff811c40e0-ffffffff811c4236: trace_set_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int trace_set_options(struct trace_array *tr, char *option);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c1cf0)
Location: kernel/trace/trace.c:4927
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_trace_options_write
  - kernel/trace/trace.c:apply_trace_boot_options
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff811c1cf0-ffffffff811c1e46: trace_set_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int trace_set_options(struct trace_array *tr, char *option);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c2d60)
Location: kernel/trace/trace.c:5276
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_trace_options_write
  - kernel/trace/trace.c:apply_trace_boot_options
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff811c2d60-ffffffff811c2eb7: trace_set_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int trace_set_options(struct trace_array *tr, char *option);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:5350
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_trace_options_write
  - kernel/trace/trace.c:apply_trace_boot_options
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff81cb54d2-ffffffff81cb54f1: trace_set_options.cold (STB_LOCAL)
ffffffff811eda60-ffffffff811edbbf: trace_set_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int trace_set_options(struct trace_array *tr, char *option);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:5351
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_trace_options_write
  - kernel/trace/trace.c:apply_trace_boot_options
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff81e66550-ffffffff81e6656f: trace_set_options.cold (STB_LOCAL)
ffffffff81225c40-ffffffff81225dac: trace_set_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int trace_set_options(struct trace_array *tr, char *option);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:5375
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_trace_options_write
  - kernel/trace/trace.c:apply_trace_boot_options
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff8205d7d3-ffffffff8205d7f2: trace_set_options.cold (STB_LOCAL)
ffffffff81270ea0-ffffffff8127100c: trace_set_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int trace_set_options(struct trace_array *tr, char *option);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:5487
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_trace_options_write
  - kernel/trace/trace.c:apply_trace_boot_options
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff820dc0f4-ffffffff820dc113: trace_set_options.cold (STB_LOCAL)
ffffffff81288180-ffffffff812882ec: trace_set_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int trace_set_options(struct trace_array *tr, char *option);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:5505
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_trace_options_write
  - kernel/trace/trace.c:apply_trace_boot_options
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff821b7f84-ffffffff821b7fa3: trace_set_options.cold (STB_LOCAL)
ffffffff812a34a0-ffffffff812a360c: trace_set_options (STB_GLOBAL)
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
int trace_set_options(struct trace_array *tr, char *option);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff800010228668)
Location: kernel/trace/trace.c:4656
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_trace_options_write
  - kernel/trace/trace.c:apply_trace_boot_options
```
**Symbols:**

```
ffff800010228668-ffff8000102287d4: trace_set_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int trace_set_options(struct trace_array *tr, char *option);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0465cac)
Location: kernel/trace/trace.c:4656
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_trace_options_write
  - kernel/trace/trace.c:apply_trace_boot_options
```
**Symbols:**

```
c0465cac-c0465ddc: trace_set_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int trace_set_options(struct trace_array *tr, char *option);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002af100)
Location: kernel/trace/trace.c:4656
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_trace_options_write
  - kernel/trace/trace.c:apply_trace_boot_options
```
**Symbols:**

```
c0000000002af100-c0000000002af49c: trace_set_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int trace_set_options(struct trace_array *tr, char *option);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe000182faa)
Location: kernel/trace/trace.c:4656
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_trace_options_write
  - kernel/trace/trace.c:apply_trace_boot_options
```
**Symbols:**

```
ffffffe000182faa-ffffffe0001830f6: trace_set_options (STB_LOCAL)
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
int trace_set_options(struct trace_array *tr, char *option);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a3e90)
Location: kernel/trace/trace.c:4656
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_trace_options_write
  - kernel/trace/trace.c:apply_trace_boot_options
```
**Symbols:**

```
ffffffff811a3e90-ffffffff811a3fe1: trace_set_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int trace_set_options(struct trace_array *tr, char *option);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81196e60)
Location: kernel/trace/trace.c:4656
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_trace_options_write
  - kernel/trace/trace.c:apply_trace_boot_options
```
**Symbols:**

```
ffffffff81196e60-ffffffff81196fb1: trace_set_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int trace_set_options(struct trace_array *tr, char *option);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a1c60)
Location: kernel/trace/trace.c:4656
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_trace_options_write
  - kernel/trace/trace.c:apply_trace_boot_options
```
**Symbols:**

```
ffffffff811a1c60-ffffffff811a1db1: trace_set_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int trace_set_options(struct trace_array *tr, char *option);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811af9f0)
Location: kernel/trace/trace.c:4656
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_trace_options_write
  - kernel/trace/trace.c:apply_trace_boot_options
```
**Symbols:**

```
ffffffff811af9f0-ffffffff811afb41: trace_set_options (STB_LOCAL)
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
