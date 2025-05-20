# Function: <code>firmware_map_find_entry_in_list</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct firmware_map_entry *firmware_map_find_entry_in_list(u64 start, u64 end, const char *type, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffffffff8181f61d)
Location: drivers/firmware/memmap.c:227
Inline: False
Direct callers:
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
  - drivers/firmware/memmap.c:firmware_map_remove
```
**Symbols:**

```
ffffffff8181f61d-ffffffff8181f67d: firmware_map_find_entry_in_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct firmware_map_entry *firmware_map_find_entry_in_list(u64 start, u64 end, const char *type, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffffffff81899d18)
Location: drivers/firmware/memmap.c:227
Inline: False
Direct callers:
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
```
**Symbols:**

```
ffffffff81899d18-ffffffff81899d76: firmware_map_find_entry_in_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct firmware_map_entry *firmware_map_find_entry_in_list(u64 start, u64 end, const char *type, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffffffff818ce3c4)
Location: drivers/firmware/memmap.c:227
Inline: False
Direct callers:
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
```
**Symbols:**

```
ffffffff818ce3c4-ffffffff818ce422: firmware_map_find_entry_in_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct firmware_map_entry *firmware_map_find_entry_in_list(u64 start, u64 end, const char *type, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffffffff81905880)
Location: drivers/firmware/memmap.c:227
Inline: False
Direct callers:
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
```
**Symbols:**

```
ffffffff81905880-ffffffff819058de: firmware_map_find_entry_in_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct firmware_map_entry *firmware_map_find_entry_in_list(u64 start, u64 end, const char *type, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffffffff8198f8f3)
Location: drivers/firmware/memmap.c:227
Inline: False
Direct callers:
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
```
**Symbols:**

```
ffffffff8198f8f3-ffffffff8198f951: firmware_map_find_entry_in_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct firmware_map_entry *firmware_map_find_entry_in_list(u64 start, u64 end, const char *type, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffffffff819ec160)
Location: drivers/firmware/memmap.c:227
Inline: False
Direct callers:
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
```
**Symbols:**

```
ffffffff819ec160-ffffffff819ec1be: firmware_map_find_entry_in_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct firmware_map_entry *firmware_map_find_entry_in_list(u64 start, u64 end, const char *type, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffffffff81a273b0)
Location: drivers/firmware/memmap.c:227
Inline: False
Direct callers:
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
```
**Symbols:**

```
ffffffff81a273b0-ffffffff81a2740e: firmware_map_find_entry_in_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct firmware_map_entry *firmware_map_find_entry_in_list(u64 start, u64 end, const char *type, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffffffff81a97c6f)
Location: drivers/firmware/memmap.c:218
Inline: False
Direct callers:
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
```
**Symbols:**

```
ffffffff81a97c6f-ffffffff81a97cd3: firmware_map_find_entry_in_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct firmware_map_entry *firmware_map_find_entry_in_list(u64 start, u64 end, const char *type, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffffffff81acf53d)
Location: drivers/firmware/memmap.c:218
Inline: False
Direct callers:
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
```
**Symbols:**

```
ffffffff81acf53d-ffffffff81acf5a1: firmware_map_find_entry_in_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct firmware_map_entry *firmware_map_find_entry_in_list(u64 start, u64 end, const char *type, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffffffff81bc7f79)
Location: drivers/firmware/memmap.c:218
Inline: False
Direct callers:
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
```
**Symbols:**

```
ffffffff81bc7f79-ffffffff81bc7fdd: firmware_map_find_entry_in_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct firmware_map_entry *firmware_map_find_entry_in_list(u64 start, u64 end, const char *type, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffffffff81c40cb3)
Location: drivers/firmware/memmap.c:218
Inline: False
Direct callers:
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
```
**Symbols:**

```
ffffffff81c40cb3-ffffffff81c40d17: firmware_map_find_entry_in_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct firmware_map_entry *firmware_map_find_entry_in_list(u64 start, u64 end, const char *type, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffffffff81c32c16)
Location: drivers/firmware/memmap.c:218
Inline: False
Direct callers:
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
```
**Symbols:**

```
ffffffff81c32c16-ffffffff81c32c7a: firmware_map_find_entry_in_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct firmware_map_entry *firmware_map_find_entry_in_list(u64 start, u64 end, const char *type, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffffffff81d51627)
Location: drivers/firmware/memmap.c:218
Inline: False
Direct callers:
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
```
**Symbols:**

```
ffffffff81d51627-ffffffff81d5168b: firmware_map_find_entry_in_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct firmware_map_entry *firmware_map_find_entry_in_list(u64 start, u64 end, const char *type, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffffffff81f21b25)
Location: drivers/firmware/memmap.c:219
Inline: False
Direct callers:
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
```
**Symbols:**

```
ffffffff81f21b25-ffffffff81f21b8f: firmware_map_find_entry_in_list (STB_LOCAL)
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
In drivers/firmware/memmap.c (ffffffff820cc526)
Location: drivers/firmware/memmap.c:219
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
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
In drivers/firmware/memmap.c (ffffffff821507d6)
Location: drivers/firmware/memmap.c:219
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
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
In drivers/firmware/memmap.c (ffffffff82233646)
Location: drivers/firmware/memmap.c:219
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
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
struct firmware_map_entry *firmware_map_find_entry_in_list(u64 start, u64 end, const char *type, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffff800010da1124)
Location: drivers/firmware/memmap.c:218
Inline: False
Direct callers:
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
```
**Symbols:**

```
ffff800010da1124-ffff800010da11ac: firmware_map_find_entry_in_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct firmware_map_entry *firmware_map_find_entry_in_list(u64 start, u64 end, const char *type, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (c15be4e0)
Location: drivers/firmware/memmap.c:218
Inline: False
Direct callers:
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
```
**Symbols:**

```
c15be4e0-c15be560: firmware_map_find_entry_in_list (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct firmware_map_entry *firmware_map_find_entry_in_list(u64 start, u64 end, const char *type, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffffffff81a6e3ad)
Location: drivers/firmware/memmap.c:218
Inline: False
Direct callers:
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
```
**Symbols:**

```
ffffffff81a6e3ad-ffffffff81a6e411: firmware_map_find_entry_in_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct firmware_map_entry *firmware_map_find_entry_in_list(u64 start, u64 end, const char *type, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffffffff81a2a7b5)
Location: drivers/firmware/memmap.c:218
Inline: False
Direct callers:
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
```
**Symbols:**

```
ffffffff81a2a7b5-ffffffff81a2a819: firmware_map_find_entry_in_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct firmware_map_entry *firmware_map_find_entry_in_list(u64 start, u64 end, const char *type, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffffffff81ada7bd)
Location: drivers/firmware/memmap.c:218
Inline: False
Direct callers:
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
```
**Symbols:**

```
ffffffff81ada7bd-ffffffff81ada821: firmware_map_find_entry_in_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct firmware_map_entry *firmware_map_find_entry_in_list(u64 start, u64 end, const char *type, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffffffff81ae6c73)
Location: drivers/firmware/memmap.c:218
Inline: False
Direct callers:
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
```
**Symbols:**

```
ffffffff81ae6c73-ffffffff81ae6cd7: firmware_map_find_entry_in_list (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
