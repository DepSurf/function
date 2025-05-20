# Function: <code>klp_cleanup_module_patches_limited</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void klp_cleanup_module_patches_limited(struct module *mod, struct klp_patch *limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff811018e0)
Location: kernel/livepatch/core.c:852
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_going
  - kernel/livepatch/core.c:klp_module_coming
```
**Symbols:**

```
ffffffff811018e0-ffffffff81101a3c: klp_cleanup_module_patches_limited (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void klp_cleanup_module_patches_limited(struct module *mod, struct klp_patch *limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:912
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_going
  - kernel/livepatch/core.c:klp_module_coming
```
**Symbols:**

```
ffffffff81109cf0-ffffffff81109e13: klp_cleanup_module_patches_limited (STB_LOCAL)
ffffffff8110ac29-ffffffff8110ac4b: klp_cleanup_module_patches_limited.cold.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void klp_cleanup_module_patches_limited(struct module *mod, struct klp_patch *limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:912
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_going
  - kernel/livepatch/core.c:klp_module_coming
```
**Symbols:**

```
ffffffff811154c0-ffffffff811155e3: klp_cleanup_module_patches_limited (STB_LOCAL)
ffffffff81116419-ffffffff8111643b: klp_cleanup_module_patches_limited.cold.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void klp_cleanup_module_patches_limited(struct module *mod, struct klp_patch *limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:1080
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_going
  - kernel/livepatch/core.c:klp_module_coming
```
**Symbols:**

```
ffffffff8111f500-ffffffff8111f5b4: klp_cleanup_module_patches_limited (STB_LOCAL)
ffffffff811204aa-ffffffff81120533: klp_cleanup_module_patches_limited.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void klp_cleanup_module_patches_limited(struct module *mod, struct klp_patch *limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:1080
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_going
  - kernel/livepatch/core.c:klp_module_coming
```
**Symbols:**

```
ffffffff8112bc50-ffffffff8112bd04: klp_cleanup_module_patches_limited (STB_LOCAL)
ffffffff8112cbb3-ffffffff8112cc3c: klp_cleanup_module_patches_limited.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void klp_cleanup_module_patches_limited(struct module *mod, struct klp_patch *limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:1139
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_going
  - kernel/livepatch/core.c:klp_module_coming
```
**Symbols:**

```
ffffffff8113a2a0-ffffffff8113a353: klp_cleanup_module_patches_limited (STB_LOCAL)
ffffffff8113b3a5-ffffffff8113b41b: klp_cleanup_module_patches_limited.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void klp_cleanup_module_patches_limited(struct module *mod, struct klp_patch *limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:1139
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_going
  - kernel/livepatch/core.c:klp_module_coming
```
**Symbols:**

```
ffffffff81134d90-ffffffff81134e43: klp_cleanup_module_patches_limited (STB_LOCAL)
ffffffff81be30b4-ffffffff81be312a: klp_cleanup_module_patches_limited.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void klp_cleanup_module_patches_limited(struct module *mod, struct klp_patch *limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:1138
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_going
  - kernel/livepatch/core.c:klp_module_coming
```
**Symbols:**

```
ffffffff81135c10-ffffffff81135cc3: klp_cleanup_module_patches_limited (STB_LOCAL)
ffffffff81bd4e55-ffffffff81bd4ecb: klp_cleanup_module_patches_limited.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void klp_cleanup_module_patches_limited(struct module *mod, struct klp_patch *limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:1138
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_going
  - kernel/livepatch/core.c:klp_module_coming
```
**Symbols:**

```
ffffffff811583c0-ffffffff81158480: klp_cleanup_module_patches_limited (STB_LOCAL)
ffffffff81caf886-ffffffff81caf91e: klp_cleanup_module_patches_limited.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void klp_cleanup_module_patches_limited(struct module *mod, struct klp_patch *limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:1135
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_going
  - kernel/livepatch/core.c:klp_module_coming
```
**Symbols:**

```
ffffffff81181890-ffffffff8118196c: klp_cleanup_module_patches_limited (STB_LOCAL)
ffffffff81e6052a-ffffffff81e605c1: klp_cleanup_module_patches_limited.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void klp_cleanup_module_patches_limited(struct module *mod, struct klp_patch *limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:1160
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_going
  - kernel/livepatch/core.c:klp_module_coming
```
**Symbols:**

```
ffffffff811bcb20-ffffffff811bcca8: klp_cleanup_module_patches_limited (STB_LOCAL)
ffffffff8205a4a6-ffffffff8205a4cf: klp_cleanup_module_patches_limited.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void klp_cleanup_module_patches_limited(struct module *mod, struct klp_patch *limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:1188
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_going
  - kernel/livepatch/core.c:klp_module_coming
```
**Symbols:**

```
ffffffff811d0020-ffffffff811d01b0: klp_cleanup_module_patches_limited (STB_LOCAL)
ffffffff820d8d83-ffffffff820d8dac: klp_cleanup_module_patches_limited.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void klp_cleanup_module_patches_limited(struct module *mod, struct klp_patch *limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:1188
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_going
  - kernel/livepatch/core.c:klp_module_coming
```
**Symbols:**

```
ffffffff811e4c70-ffffffff811e4e00: klp_cleanup_module_patches_limited (STB_LOCAL)
ffffffff821b44bc-ffffffff821b44e5: klp_cleanup_module_patches_limited.cold (STB_LOCAL)
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void klp_cleanup_module_patches_limited(struct module *mod, struct klp_patch *limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (c0000000001ef250)
Location: kernel/livepatch/core.c:1080
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_going
  - kernel/livepatch/core.c:klp_module_coming
```
**Symbols:**

```
c0000000001ef250-c0000000001ef5b4: klp_cleanup_module_patches_limited (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void klp_cleanup_module_patches_limited(struct module *mod, struct klp_patch *limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:1080
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_going
  - kernel/livepatch/core.c:klp_module_coming
```
**Symbols:**

```
ffffffff81124230-ffffffff811242e4: klp_cleanup_module_patches_limited (STB_LOCAL)
ffffffff81125193-ffffffff8112521c: klp_cleanup_module_patches_limited.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void klp_cleanup_module_patches_limited(struct module *mod, struct klp_patch *limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:1080
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_going
  - kernel/livepatch/core.c:klp_module_coming
```
**Symbols:**

```
ffffffff81116c90-ffffffff81116d44: klp_cleanup_module_patches_limited (STB_LOCAL)
ffffffff81117bf3-ffffffff81117c7c: klp_cleanup_module_patches_limited.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void klp_cleanup_module_patches_limited(struct module *mod, struct klp_patch *limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:1080
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_going
  - kernel/livepatch/core.c:klp_module_coming
```
**Symbols:**

```
ffffffff81122120-ffffffff811221d4: klp_cleanup_module_patches_limited (STB_LOCAL)
ffffffff81123083-ffffffff8112310c: klp_cleanup_module_patches_limited.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void klp_cleanup_module_patches_limited(struct module *mod, struct klp_patch *limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:1080
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_going
  - kernel/livepatch/core.c:klp_module_coming
```
**Symbols:**

```
ffffffff8112e730-ffffffff8112e7e4: klp_cleanup_module_patches_limited (STB_LOCAL)
ffffffff8112f693-ffffffff8112f71c: klp_cleanup_module_patches_limited.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
