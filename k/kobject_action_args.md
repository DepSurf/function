# Function: <code>kobject_action_args</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff818efa20)
Location: lib/kobject_uevent.c:109
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_synth_uevent
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
In lib/kobject_uevent.c (ffffffff81975e60)
Location: lib/kobject_uevent.c:111
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_synth_uevent
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
In lib/kobject_uevent.c (ffffffff819d263f)
Location: lib/kobject_uevent.c:114
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_synth_uevent
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
In lib/kobject_uevent.c (ffffffff81a0bbaf)
Location: lib/kobject_uevent.c:114
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_synth_uevent
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
In lib/kobject_uevent.c (ffffffff81a7b58d)
Location: lib/kobject_uevent.c:114
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_synth_uevent
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
In lib/kobject_uevent.c (ffffffff81ab28ed)
Location: lib/kobject_uevent.c:114
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_synth_uevent
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kobject_action_args(const char *buf, size_t count, struct kobj_uevent_env **ret_env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff815ecab0)
Location: lib/kobject_uevent.c:114
Inline: False
Direct callers:
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff815ecab0-ffffffff815ecc35: kobject_action_args (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kobject_action_args(const char *buf, size_t count, struct kobj_uevent_env **ret_env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81611290)
Location: lib/kobject_uevent.c:114
Inline: False
Direct callers:
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff81611290-ffffffff81611415: kobject_action_args (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kobject_action_args(const char *buf, size_t count, struct kobj_uevent_env **ret_env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff815f4950)
Location: lib/kobject_uevent.c:114
Inline: False
Direct callers:
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff815f4950-ffffffff815f4ade: kobject_action_args (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kobject_action_args(const char *buf, size_t count, struct kobj_uevent_env **ret_env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81661d20)
Location: lib/kobject_uevent.c:114
Inline: False
Direct callers:
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff81661d20-ffffffff81661eae: kobject_action_args (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kobject_action_args(const char *buf, size_t count, struct kobj_uevent_env **ret_env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff8177ba30)
Location: lib/kobject_uevent.c:114
Inline: False
Direct callers:
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff8177ba30-ffffffff8177bbcf: kobject_action_args (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kobject_action_args(const char *buf, size_t count, struct kobj_uevent_env **ret_env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff82024c90)
Location: lib/kobject_uevent.c:114
Inline: False
Direct callers:
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff82024c90-ffffffff82024e2f: kobject_action_args (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kobject_action_args(const char *buf, size_t count, struct kobj_uevent_env **ret_env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff820a4da0)
Location: lib/kobject_uevent.c:114
Inline: False
Direct callers:
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff820a4da0-ffffffff820a4f3f: kobject_action_args (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kobject_action_args(const char *buf, size_t count, struct kobj_uevent_env **ret_env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff8217ced0)
Location: lib/kobject_uevent.c:114
Inline: False
Direct callers:
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff8217ced0-ffffffff8217d09e: kobject_action_args (STB_LOCAL)
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
In lib/kobject_uevent.c (ffff800010d8cc10)
Location: lib/kobject_uevent.c:114
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_synth_uevent
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
In lib/kobject_uevent.c (c0e86ff0)
Location: lib/kobject_uevent.c:114
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_synth_uevent
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
In lib/kobject_uevent.c (c000000000ece9e8)
Location: lib/kobject_uevent.c:114
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_synth_uevent
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
In lib/kobject_uevent.c (ffffffe0008b5a3c)
Location: lib/kobject_uevent.c:114
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_synth_uevent
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
In lib/kobject_uevent.c (ffffffff81a5173d)
Location: lib/kobject_uevent.c:114
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_synth_uevent
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
In lib/kobject_uevent.c (ffffffff81a0e83d)
Location: lib/kobject_uevent.c:114
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_synth_uevent
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
In lib/kobject_uevent.c (ffffffff81abdb2d)
Location: lib/kobject_uevent.c:114
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_synth_uevent
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
In lib/kobject_uevent.c (ffffffff81ac9fad)
Location: lib/kobject_uevent.c:114
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_synth_uevent
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
