# Function: <code>create_rule</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct landlock_rule *create_rule(const struct landlock_object * object, const const struct landlock_layer[0] * layers, const u32 num_layers, const const struct landlock_layer * new_layer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ruleset.c (ffffffff81537ad0)
Location: security/landlock/ruleset.c:69
Inline: False
Direct callers:
  - security/landlock/ruleset.c:insert_rule
  - security/landlock/ruleset.c:insert_rule
```
**Symbols:**

```
ffffffff81537ad0-ffffffff81537bd6: create_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct landlock_rule *create_rule(const struct landlock_object * object, const const struct landlock_layer[0] * layers, const u32 num_layers, const const struct landlock_layer * new_layer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ruleset.c (ffffffff815962d0)
Location: security/landlock/ruleset.c:69
Inline: False
Direct callers:
  - security/landlock/ruleset.c:insert_rule
  - security/landlock/ruleset.c:insert_rule
```
**Symbols:**

```
ffffffff815962d0-ffffffff815963d6: create_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct landlock_rule *create_rule(const struct landlock_object * object, const const struct landlock_layer[0] * layers, const u32 num_layers, const const struct landlock_layer * new_layer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ruleset.c (ffffffff81638660)
Location: security/landlock/ruleset.c:72
Inline: False
Direct callers:
  - security/landlock/ruleset.c:insert_rule
  - security/landlock/ruleset.c:insert_rule
```
**Symbols:**

```
ffffffff81638660-ffffffff8163875c: create_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct landlock_rule *create_rule(const struct landlock_object * object, const const struct landlock_layer[0] * layers, const u32 num_layers, const const struct landlock_layer * new_layer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ruleset.c (ffffffff816efb00)
Location: security/landlock/ruleset.c:72
Inline: False
Direct callers:
  - security/landlock/ruleset.c:insert_rule
  - security/landlock/ruleset.c:insert_rule
```
**Symbols:**

```
ffffffff816efb00-ffffffff816efbfc: create_rule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct landlock_rule *create_rule(const struct landlock_object * object, const const struct landlock_layer[0] * layers, const u32 num_layers, const const struct landlock_layer * new_layer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/landlock/ruleset.c (0)
Location: security/landlock/ruleset.c:72
Inline: False
Direct callers:
  - security/landlock/ruleset.c:insert_rule
  - security/landlock/ruleset.c:insert_rule
```
**Symbols:**

```
ffffffff81729fb0-ffffffff8172a115: create_rule (STB_LOCAL)
ffffffff820f4aa8-ffffffff820f4acb: create_rule.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/landlock/ruleset.c (ffffffff8176b3b0)
Location: security/landlock/ruleset.c:99
Inline: True
Direct callers:
  - security/landlock/ruleset.c:insert_rule
  - security/landlock/ruleset.c:insert_rule
```
**Symbols:**

```
ffffffff8176b3b0-ffffffff8176b51f: create_rule.isra.0 (STB_LOCAL)
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
</ul>
