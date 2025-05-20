# Function: <code>new_idmap_permitted</code>

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
In kernel/user_namespace.c (ffffffff8111ea25)
Location: kernel/user_namespace.c:822
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
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
In kernel/user_namespace.c (ffffffff81126991)
Location: kernel/user_namespace.c:815
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
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
In kernel/user_namespace.c (ffffffff8113047e)
Location: kernel/user_namespace.c:861
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
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
In kernel/user_namespace.c (ffffffff81131a4f)
Location: kernel/user_namespace.c:862
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
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
In kernel/user_namespace.c (ffffffff8113e859)
Location: kernel/user_namespace.c:1095
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
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
In kernel/user_namespace.c (ffffffff8114d2bb)
Location: kernel/user_namespace.c:1092
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
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
In kernel/user_namespace.c (ffffffff81159ee1)
Location: kernel/user_namespace.c:1096
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
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
In kernel/user_namespace.c (ffffffff8116660a)
Location: kernel/user_namespace.c:1090
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
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
In kernel/user_namespace.c (ffffffff811724ca)
Location: kernel/user_namespace.c:1090
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
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
In kernel/user_namespace.c (ffffffff811841b4)
Location: kernel/user_namespace.c:1090
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
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
In kernel/user_namespace.c (ffffffff81180f14)
Location: kernel/user_namespace.c:1090
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool new_idmap_permitted(const struct file *file, struct user_namespace *ns, int cap_setid, struct uid_gid_map *new_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81181c00)
Location: kernel/user_namespace.c:1145
Inline: False
Direct callers:
  - kernel/user_namespace.c:map_write
```
**Symbols:**

```
ffffffff81181c00-ffffffff81181d99: new_idmap_permitted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool new_idmap_permitted(const struct file *file, struct user_namespace *ns, int cap_setid, struct uid_gid_map *new_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/user_namespace.c (0)
Location: kernel/user_namespace.c:1161
Inline: False
Direct callers:
  - kernel/user_namespace.c:map_write
```
**Symbols:**

```
ffffffff811a9ba0-ffffffff811a9d53: new_idmap_permitted (STB_LOCAL)
ffffffff81cb3366-ffffffff81cb3381: new_idmap_permitted.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool new_idmap_permitted(const struct file *file, struct user_namespace *ns, int cap_setid, struct uid_gid_map *new_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/user_namespace.c (0)
Location: kernel/user_namespace.c:1166
Inline: False
Direct callers:
  - kernel/user_namespace.c:map_write
```
**Symbols:**

```
ffffffff811db050-ffffffff811db245: new_idmap_permitted (STB_LOCAL)
ffffffff81e64158-ffffffff81e64173: new_idmap_permitted.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool new_idmap_permitted(const struct file *file, struct user_namespace *ns, int cap_setid, struct uid_gid_map *new_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/user_namespace.c (0)
Location: kernel/user_namespace.c:1166
Inline: False
Direct callers:
  - kernel/user_namespace.c:map_write
```
**Symbols:**

```
ffffffff812208e0-ffffffff81220ad5: new_idmap_permitted (STB_LOCAL)
ffffffff8205c49a-ffffffff8205c4b5: new_idmap_permitted.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool new_idmap_permitted(const struct file *file, struct user_namespace *ns, int cap_setid, struct uid_gid_map *new_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/user_namespace.c (0)
Location: kernel/user_namespace.c:1166
Inline: False
Direct callers:
  - kernel/user_namespace.c:map_write
```
**Symbols:**

```
ffffffff81236cb0-ffffffff81236f12: new_idmap_permitted (STB_LOCAL)
ffffffff820dadf6-ffffffff820dae12: new_idmap_permitted.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool new_idmap_permitted(const struct file *file, struct user_namespace *ns, int cap_setid, struct uid_gid_map *new_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/user_namespace.c (0)
Location: kernel/user_namespace.c:1169
Inline: False
Direct callers:
  - kernel/user_namespace.c:map_write
```
**Symbols:**

```
ffffffff812504a0-ffffffff81250702: new_idmap_permitted (STB_LOCAL)
ffffffff821b6af4-ffffffff821b6b10: new_idmap_permitted.cold (STB_LOCAL)
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
In kernel/user_namespace.c (ffff8000101e6158)
Location: kernel/user_namespace.c:1090
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
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
In kernel/user_namespace.c (c0426bfc)
Location: kernel/user_namespace.c:1090
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
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
In kernel/user_namespace.c (c000000000256a9c)
Location: kernel/user_namespace.c:1090
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
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
In kernel/user_namespace.c (ffffffe00015bd9a)
Location: kernel/user_namespace.c:1090
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
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
In kernel/user_namespace.c (ffffffff8116aaea)
Location: kernel/user_namespace.c:1090
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
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
In kernel/user_namespace.c (ffffffff8115dcea)
Location: kernel/user_namespace.c:1090
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
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
In kernel/user_namespace.c (ffffffff811688ba)
Location: kernel/user_namespace.c:1090
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
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
In kernel/user_namespace.c (ffffffff81175faa)
Location: kernel/user_namespace.c:1090
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
```
</details>
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
