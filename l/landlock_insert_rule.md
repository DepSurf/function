# Function: <code>landlock_insert_rule</code>

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
int landlock_insert_rule(const struct landlock_ruleset * ruleset, const struct landlock_object * object, const u32 access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ruleset.c (ffffffff81538100)
Location: security/landlock/ruleset.c:230
Inline: False
Direct callers:
  - security/landlock/fs.c:landlock_append_fs_rule
```
**Symbols:**

```
ffffffff81538100-ffffffff8153814a: landlock_insert_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int landlock_insert_rule(const struct landlock_ruleset * ruleset, const struct landlock_object * object, const u32 access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ruleset.c (ffffffff815967c0)
Location: security/landlock/ruleset.c:230
Inline: False
Direct callers:
  - security/landlock/fs.c:landlock_append_fs_rule
```
**Symbols:**

```
ffffffff815967c0-ffffffff8159680a: landlock_insert_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int landlock_insert_rule(const struct landlock_ruleset * ruleset, const struct landlock_object * object, const access_mask_t access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ruleset.c (ffffffff81638c80)
Location: security/landlock/ruleset.c:231
Inline: False
Direct callers:
  - security/landlock/fs.c:landlock_append_fs_rule
```
**Symbols:**

```
ffffffff81638c80-ffffffff81638cd6: landlock_insert_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int landlock_insert_rule(const struct landlock_ruleset * ruleset, const struct landlock_object * object, const access_mask_t access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ruleset.c (ffffffff816f0170)
Location: security/landlock/ruleset.c:231
Inline: False
Direct callers:
  - security/landlock/fs.c:landlock_append_fs_rule
```
**Symbols:**

```
ffffffff816f0170-ffffffff816f01c6: landlock_insert_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int landlock_insert_rule(const struct landlock_ruleset * ruleset, const struct landlock_object * object, const access_mask_t access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ruleset.c (ffffffff8172a510)
Location: security/landlock/ruleset.c:231
Inline: False
Direct callers:
  - security/landlock/fs.c:landlock_append_fs_rule
```
**Symbols:**

```
ffffffff8172a510-ffffffff8172a566: landlock_insert_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int landlock_insert_rule(const struct landlock_ruleset * ruleset, const struct landlock_id id, const access_mask_t access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ruleset.c (ffffffff8176bbc0)
Location: security/landlock/ruleset.c:294
Inline: False
Direct callers:
  - security/landlock/fs.c:landlock_append_fs_rule
  - security/landlock/net.c:landlock_append_net_rule
```
**Symbols:**

```
ffffffff8176bbc0-ffffffff8176bc1f: landlock_insert_rule (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const u32 access</code> ➡️ <code>const access_mask_t access</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct landlock_id id</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct landlock_object * object</code>
</li>
</ul>
</details>
</li>
</ul>
