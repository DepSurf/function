# Function: <code>free_ftrace_mod</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_ftrace_mod(struct ftrace_mod_load *ftrace_mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81154dc0)
Location: kernel/trace/ftrace.c:1311
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_regex_open
```
**Symbols:**

```
ffffffff81154dc0-ffffffff81154e0a: free_ftrace_mod (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_ftrace_mod(struct ftrace_mod_load *ftrace_mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811615f0)
Location: kernel/trace/ftrace.c:1287
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_regex_open
```
**Symbols:**

```
ffffffff811615f0-ffffffff8116163a: free_ftrace_mod (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_ftrace_mod(struct ftrace_mod_load *ftrace_mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81170510)
Location: kernel/trace/ftrace.c:1276
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_regex_open
```
**Symbols:**

```
ffffffff81170510-ffffffff8117055a: free_ftrace_mod (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_ftrace_mod(struct ftrace_mod_load *ftrace_mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8117df00)
Location: kernel/trace/ftrace.c:1225
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_regex_open
```
**Symbols:**

```
ffffffff8117df00-ffffffff8117df4a: free_ftrace_mod (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_ftrace_mod(struct ftrace_mod_load *ftrace_mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118afa0)
Location: kernel/trace/ftrace.c:1222
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_regex_open
```
**Symbols:**

```
ffffffff8118afa0-ffffffff8118afeb: free_ftrace_mod (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_ftrace_mod(struct ftrace_mod_load *ftrace_mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81196e90)
Location: kernel/trace/ftrace.c:1223
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_regex_open
```
**Symbols:**

```
ffffffff81196e90-ffffffff81196edb: free_ftrace_mod (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b1ccc)
Location: kernel/trace/ftrace.c:1211
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:cache_mod
  - kernel/trace/ftrace.c:cache_mod
  - kernel/trace/ftrace.c:ftrace_regex_open
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
In kernel/trace/ftrace.c (ffffffff811af73c)
Location: kernel/trace/ftrace.c:1210
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:cache_mod
  - kernel/trace/ftrace.c:cache_mod
  - kernel/trace/ftrace.c:ftrace_regex_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811aff9b)
Location: kernel/trace/ftrace.c:1210
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:cache_mod
  - kernel/trace/ftrace.c:cache_mod
  - kernel/trace/ftrace.c:ftrace_regex_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811d9e17)
Location: kernel/trace/ftrace.c:1211
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:cache_mod
  - kernel/trace/ftrace.c:cache_mod
  - kernel/trace/ftrace.c:ftrace_regex_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8120f6e6)
Location: kernel/trace/ftrace.c:1205
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:cache_mod
  - kernel/trace/ftrace.c:cache_mod
  - kernel/trace/ftrace.c:ftrace_regex_open
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81258a39)
Location: kernel/trace/ftrace.c:1205
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:cache_mod
  - kernel/trace/ftrace.c:cache_mod
  - kernel/trace/ftrace.c:ftrace_regex_open
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
In kernel/trace/ftrace.c (ffffffff8126fe09)
Location: kernel/trace/ftrace.c:1236
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:cache_mod
  - kernel/trace/ftrace.c:cache_mod
  - kernel/trace/ftrace.c:ftrace_regex_open
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8128a2b9)
Location: kernel/trace/ftrace.c:1237
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:cache_mod
  - kernel/trace/ftrace.c:cache_mod
  - kernel/trace/ftrace.c:ftrace_regex_open
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
void free_ftrace_mod(struct ftrace_mod_load *ftrace_mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffff80001020f2f8)
Location: kernel/trace/ftrace.c:1223
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_regex_open
```
**Symbols:**

```
ffff80001020f2f8-ffff80001020f34c: free_ftrace_mod (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_ftrace_mod(struct ftrace_mod_load *ftrace_mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c044e304)
Location: kernel/trace/ftrace.c:1223
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_regex_open
```
**Symbols:**

```
c044e304-c044e34c: free_ftrace_mod (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_ftrace_mod(struct ftrace_mod_load *ftrace_mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c00000000028df90)
Location: kernel/trace/ftrace.c:1223
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_regex_open
```
**Symbols:**

```
c00000000028df90-c00000000028e024: free_ftrace_mod (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void free_ftrace_mod(struct ftrace_mod_load *ftrace_mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffe000170048)
Location: kernel/trace/ftrace.c:1223
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_regex_open
```
**Symbols:**

```
ffffffe000170048-ffffffe000170090: free_ftrace_mod (STB_LOCAL)
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
void free_ftrace_mod(struct ftrace_mod_load *ftrace_mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118f4b0)
Location: kernel/trace/ftrace.c:1223
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_regex_open
```
**Symbols:**

```
ffffffff8118f4b0-ffffffff8118f4fb: free_ftrace_mod (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_ftrace_mod(struct ftrace_mod_load *ftrace_mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811825f0)
Location: kernel/trace/ftrace.c:1223
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_regex_open
```
**Symbols:**

```
ffffffff811825f0-ffffffff8118263b: free_ftrace_mod (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_ftrace_mod(struct ftrace_mod_load *ftrace_mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118d280)
Location: kernel/trace/ftrace.c:1223
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_regex_open
```
**Symbols:**

```
ffffffff8118d280-ffffffff8118d2cb: free_ftrace_mod (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_ftrace_mod(struct ftrace_mod_load *ftrace_mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119ae00)
Location: kernel/trace/ftrace.c:1223
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:ftrace_mod_callback
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_regex_open
```
**Symbols:**

```
ffffffff8119ae00-ffffffff8119ae4b: free_ftrace_mod (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
