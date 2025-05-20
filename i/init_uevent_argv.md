# Function: <code>init_uevent_argv</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff813ed009)
Location: lib/kobject_uevent.c:129
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff814333d5)
Location: lib/kobject_uevent.c:129
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff8144f645)
Location: lib/kobject_uevent.c:129
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff818ef834)
Location: lib/kobject_uevent.c:270
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81975c86)
Location: lib/kobject_uevent.c:272
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff819d22b1)
Location: lib/kobject_uevent.c:251
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81a0b656)
Location: lib/kobject_uevent.c:252
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81a7b0c6)
Location: lib/kobject_uevent.c:252
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81ab2426)
Location: lib/kobject_uevent.c:252
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int init_uevent_argv(struct kobj_uevent_env *env, const char *subsystem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff815ebf80)
Location: lib/kobject_uevent.c:252
Inline: False
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff815ebf80-ffffffff815ec000: init_uevent_argv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int init_uevent_argv(struct kobj_uevent_env *env, const char *subsystem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81610760)
Location: lib/kobject_uevent.c:252
Inline: False
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff81610760-ffffffff816107e0: init_uevent_argv (STB_LOCAL)
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
In lib/kobject_uevent.c (ffffffff815f47ef)
Location: lib/kobject_uevent.c:252
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
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
In lib/kobject_uevent.c (ffffffff81661b62)
Location: lib/kobject_uevent.c:252
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int init_uevent_argv(struct kobj_uevent_env *env, const char *subsystem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject_uevent.c (0)
Location: lib/kobject_uevent.c:252
Inline: False
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff8177ae20-ffffffff8177aef3: init_uevent_argv (STB_LOCAL)
ffffffff81ea5b6c-ffffffff81ea5b85: init_uevent_argv.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int init_uevent_argv(struct kobj_uevent_env *env, const char *subsystem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff82023cb0)
Location: lib/kobject_uevent.c:252
Inline: False
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff82023cb0-ffffffff82023d98: init_uevent_argv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int init_uevent_argv(struct kobj_uevent_env *env, const char *subsystem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff820a3d20)
Location: lib/kobject_uevent.c:252
Inline: False
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff820a3d20-ffffffff820a3e99: init_uevent_argv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int init_uevent_argv(struct kobj_uevent_env *env, const char *subsystem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff8217be00)
Location: lib/kobject_uevent.c:252
Inline: False
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff8217be00-ffffffff8217bf61: init_uevent_argv (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffff800010d8c5f0)
Location: lib/kobject_uevent.c:252
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (c0e86974)
Location: lib/kobject_uevent.c:252
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (c000000000ece654)
Location: lib/kobject_uevent.c:252
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffe0008b5756)
Location: lib/kobject_uevent.c:252
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81a51276)
Location: lib/kobject_uevent.c:252
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81a0e376)
Location: lib/kobject_uevent.c:252
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81abd666)
Location: lib/kobject_uevent.c:252
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81ac9ae6)
Location: lib/kobject_uevent.c:252
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_env
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
