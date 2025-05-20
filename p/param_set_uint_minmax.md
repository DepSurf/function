# Function: <code>param_set_uint_minmax</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int param_set_uint_minmax(const char *val, const struct kernel_param *kp, unsigned int min, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810de3a0)
Location: kernel/params.c:246
Inline: False
```
**Symbols:**

```
ffffffff810de3a0-ffffffff810de415: param_set_uint_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int param_set_uint_minmax(const char *val, const struct kernel_param *kp, unsigned int min, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810f80c0)
Location: kernel/params.c:246
Inline: False
```
**Symbols:**

```
ffffffff810f80c0-ffffffff810f8148: param_set_uint_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int param_set_uint_minmax(const char *val, const struct kernel_param *kp, unsigned int min, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff8111aa80)
Location: kernel/params.c:246
Inline: False
Direct callers:
  - mm/page_reporting.c:page_order_update_notify
```
**Symbols:**

```
ffffffff8111aa80-ffffffff8111ab08: param_set_uint_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int param_set_uint_minmax(const char *val, const struct kernel_param *kp, unsigned int min, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff81127cf0)
Location: kernel/params.c:247
Inline: False
Direct callers:
  - mm/page_reporting.c:page_order_update_notify
```
**Symbols:**

```
ffffffff81127cf0-ffffffff81127d78: param_set_uint_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int param_set_uint_minmax(const char *val, const struct kernel_param *kp, unsigned int min, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff811322d0)
Location: kernel/params.c:244
Inline: False
Direct callers:
  - mm/page_reporting.c:page_order_update_notify
```
**Symbols:**

```
ffffffff811322d0-ffffffff81132358: param_set_uint_minmax (STB_GLOBAL)
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
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
