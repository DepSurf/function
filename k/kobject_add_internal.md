# Function: <code>kobject_add_internal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kobject_add_internal(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff813ec060)
Location: lib/kobject.c:200
Inline: False
Direct callers:
  - lib/kobject.c:kobject_add
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init_and_add
```
**Symbols:**

```
ffffffff813ec060-ffffffff813ec393: kobject_add_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kobject_add_internal(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81432360)
Location: lib/kobject.c:200
Inline: False
Direct callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
```
**Symbols:**

```
ffffffff81432360-ffffffff81432680: kobject_add_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kobject_add_internal(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8144e5d0)
Location: lib/kobject.c:200
Inline: False
Direct callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
```
**Symbols:**

```
ffffffff8144e5d0-ffffffff8144e8f0: kobject_add_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kobject_add_internal(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff818ee860)
Location: lib/kobject.c:200
Inline: False
Direct callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
```
**Symbols:**

```
ffffffff818ee860-ffffffff818eeb07: kobject_add_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kobject_add_internal(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81974b20)
Location: lib/kobject.c:200
Inline: False
Direct callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
```
**Symbols:**

```
ffffffff81974b20-ffffffff81974dca: kobject_add_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int kobject_add_internal(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:217
Inline: False
Direct callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
```
**Symbols:**

```
ffffffff819d1130-ffffffff819d1388: kobject_add_internal (STB_LOCAL)
ffffffff819d17b8-ffffffff819d1803: kobject_add_internal.cold.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int kobject_add_internal(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:217
Inline: False
Direct callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
```
**Symbols:**

```
ffffffff81a0a690-ffffffff81a0a8e8: kobject_add_internal (STB_LOCAL)
ffffffff81a0ad18-ffffffff81a0ad63: kobject_add_internal.cold.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int kobject_add_internal(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:225
Inline: False
Direct callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
```
**Symbols:**

```
ffffffff81a79ff0-ffffffff81a7a29b: kobject_add_internal (STB_LOCAL)
ffffffff81a7a6e9-ffffffff81a7a735: kobject_add_internal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int kobject_add_internal(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:225
Inline: False
Direct callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
```
**Symbols:**

```
ffffffff81ab1350-ffffffff81ab15fb: kobject_add_internal (STB_LOCAL)
ffffffff81ab1a49-ffffffff81ab1a95: kobject_add_internal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int kobject_add_internal(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:225
Inline: False
Direct callers:
  - lib/kobject.c:kset_create_and_add
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
```
**Symbols:**

```
ffffffff815eb130-ffffffff815eb2f5: kobject_add_internal (STB_LOCAL)
ffffffff815ebd4c-ffffffff815ebd98: kobject_add_internal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int kobject_add_internal(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:225
Inline: False
Direct callers:
  - lib/kobject.c:kset_create_and_add
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
```
**Symbols:**

```
ffffffff8160fa50-ffffffff8160fc15: kobject_add_internal (STB_LOCAL)
ffffffff81bf4ad3-ffffffff81bf4b1f: kobject_add_internal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int kobject_add_internal(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:225
Inline: False
Direct callers:
  - lib/kobject.c:kset_create_and_add
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
```
**Symbols:**

```
ffffffff815f3190-ffffffff815f3355: kobject_add_internal (STB_LOCAL)
ffffffff81be69dc-ffffffff81be6a28: kobject_add_internal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int kobject_add_internal(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:225
Inline: False
Direct callers:
  - lib/kobject.c:kset_create_and_add
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
```
**Symbols:**

```
ffffffff81660360-ffffffff81660522: kobject_add_internal (STB_LOCAL)
ffffffff81cdf2c9-ffffffff81cdf315: kobject_add_internal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int kobject_add_internal(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:193
Inline: False
Direct callers:
  - lib/kobject.c:kset_create_and_add
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
```
**Symbols:**

```
ffffffff81779d40-ffffffff81779fe1: kobject_add_internal (STB_LOCAL)
ffffffff81ea5a9e-ffffffff81ea5ae9: kobject_add_internal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kobject_add_internal(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff82022d80)
Location: lib/kobject.c:201
Inline: False
Direct callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
```
**Symbols:**

```
ffffffff82022d80-ffffffff82023075: kobject_add_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kobject_add_internal(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff820a2df0)
Location: lib/kobject.c:203
Inline: False
Direct callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
```
**Symbols:**

```
ffffffff820a2df0-ffffffff820a30e5: kobject_add_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kobject_add_internal(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8217ae70)
Location: lib/kobject.c:210
Inline: False
Direct callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
```
**Symbols:**

```
ffffffff8217ae70-ffffffff8217b159: kobject_add_internal (STB_LOCAL)
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
int kobject_add_internal(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffff800010d8ade8)
Location: lib/kobject.c:225
Inline: False
Direct callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
```
**Symbols:**

```
ffff800010d8ade8-ffff800010d8b158: kobject_add_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kobject_add_internal(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (c0e85a2c)
Location: lib/kobject.c:225
Inline: False
Direct callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
```
**Symbols:**

```
c0e85a2c-c0e85d98: kobject_add_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kobject_add_internal(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (c000000000eccbd0)
Location: lib/kobject.c:225
Inline: False
Direct callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
```
**Symbols:**

```
c000000000eccbd0-c000000000eccfdc: kobject_add_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kobject_add_internal(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffe0008b47b0)
Location: lib/kobject.c:225
Inline: False
Direct callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
```
**Symbols:**

```
ffffffe0008b47b0-ffffffe0008b4a42: kobject_add_internal (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int kobject_add_internal(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:225
Inline: False
Direct callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
```
**Symbols:**

```
ffffffff81a501a0-ffffffff81a5044b: kobject_add_internal (STB_LOCAL)
ffffffff81a50899-ffffffff81a508e5: kobject_add_internal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int kobject_add_internal(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:225
Inline: False
Direct callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
```
**Symbols:**

```
ffffffff81a0d2a0-ffffffff81a0d54b: kobject_add_internal (STB_LOCAL)
ffffffff81a0d999-ffffffff81a0d9e5: kobject_add_internal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int kobject_add_internal(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:225
Inline: False
Direct callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
```
**Symbols:**

```
ffffffff81abc590-ffffffff81abc83b: kobject_add_internal (STB_LOCAL)
ffffffff81abcc89-ffffffff81abccd5: kobject_add_internal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int kobject_add_internal(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:225
Inline: False
Direct callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init_and_add
  - lib/kobject.c:kobject_add
```
**Symbols:**

```
ffffffff81ac8a10-ffffffff81ac8cb9: kobject_add_internal (STB_LOCAL)
ffffffff81ac910c-ffffffff81ac9158: kobject_add_internal.cold (STB_LOCAL)
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
