# Function: <code>drop_sysctl_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void drop_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81284840)
Location: fs/proc/proc_sysctl.c:1544
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:put_links
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
```
**Symbols:**

```
ffffffff81284840-ffffffff8128491b: drop_sysctl_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void drop_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812b1910)
Location: fs/proc/proc_sysctl.c:1550
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:put_links
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff812b1910-ffffffff812b19eb: drop_sysctl_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void drop_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812c71b0)
Location: fs/proc/proc_sysctl.c:1556
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:put_links
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff812c71b0-ffffffff812c728b: drop_sysctl_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void drop_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812d4340)
Location: fs/proc/proc_sysctl.c:1620
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:put_links
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff812d4340-ffffffff812d44f4: drop_sysctl_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void drop_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812f8b70)
Location: fs/proc/proc_sysctl.c:1621
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:put_links
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff812f8b70-ffffffff812f8d24: drop_sysctl_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void drop_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81326470)
Location: fs/proc/proc_sysctl.c:1623
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:put_links
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff81326470-ffffffff8132661b: drop_sysctl_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void drop_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff8133d340)
Location: fs/proc/proc_sysctl.c:1622
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:put_links
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff8133d340-ffffffff8133d4f2: drop_sysctl_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void drop_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81365650)
Location: fs/proc/proc_sysctl.c:1647
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:put_links
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff81365650-ffffffff813657fb: drop_sysctl_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void drop_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff8137d8e0)
Location: fs/proc/proc_sysctl.c:1647
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:put_links
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff8137d8e0-ffffffff8137da8b: drop_sysctl_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void drop_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813c7ee0)
Location: fs/proc/proc_sysctl.c:1630
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:put_links
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:get_subdir
  - fs/proc/proc_sysctl.c:get_subdir
  - fs/proc/proc_sysctl.c:get_subdir
  - fs/proc/proc_sysctl.c:get_subdir
  - fs/proc/proc_sysctl.c:get_subdir
  - fs/proc/proc_sysctl.c:get_subdir
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff813c7ee0-ffffffff813c802f: drop_sysctl_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void drop_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813d9ed0)
Location: fs/proc/proc_sysctl.c:1630
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:put_links
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:get_subdir
  - fs/proc/proc_sysctl.c:get_subdir
  - fs/proc/proc_sysctl.c:get_subdir
  - fs/proc/proc_sysctl.c:get_subdir
  - fs/proc/proc_sysctl.c:get_subdir
  - fs/proc/proc_sysctl.c:get_subdir
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff813d9ed0-ffffffff813da01f: drop_sysctl_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void drop_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813e0d20)
Location: fs/proc/proc_sysctl.c:1634
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:put_links
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff813e0d20-ffffffff813e0e6f: drop_sysctl_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void drop_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff814327d0)
Location: fs/proc/proc_sysctl.c:1634
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:put_links
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff814327d0-ffffffff8143291f: drop_sysctl_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void drop_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff814abe30)
Location: fs/proc/proc_sysctl.c:1703
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:put_links
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff814abe30-ffffffff814abfb0: drop_sysctl_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void drop_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81542610)
Location: fs/proc/proc_sysctl.c:1702
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:put_links
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff81542610-ffffffff81542790: drop_sysctl_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void drop_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff8157a770)
Location: fs/proc/proc_sysctl.c:1493
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:put_links
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:sysctl_mkdir_p
  - fs/proc/proc_sysctl.c:sysctl_mkdir_p
  - fs/proc/proc_sysctl.c:sysctl_mkdir_p
  - fs/proc/proc_sysctl.c:sysctl_mkdir_p
  - fs/proc/proc_sysctl.c:sysctl_mkdir_p
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff8157a770-ffffffff8157a8f2: drop_sysctl_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void drop_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff815b3090)
Location: fs/proc/proc_sysctl.c:1489
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:put_links
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:sysctl_mkdir_p
  - fs/proc/proc_sysctl.c:sysctl_mkdir_p
  - fs/proc/proc_sysctl.c:sysctl_mkdir_p
  - fs/proc/proc_sysctl.c:sysctl_mkdir_p
  - fs/proc/proc_sysctl.c:sysctl_mkdir_p
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff815b3090-ffffffff815b31d6: drop_sysctl_table (STB_LOCAL)
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
void drop_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffff80001044a958)
Location: fs/proc/proc_sysctl.c:1647
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:put_links
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffff80001044a958-ffff80001044abe0: drop_sysctl_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void drop_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (c060f814)
Location: fs/proc/proc_sysctl.c:1647
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:put_links
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
c060f814-c060fa34: drop_sysctl_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void drop_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (c000000000561080)
Location: fs/proc/proc_sysctl.c:1647
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:put_links
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
c000000000561080-c0000000005613f0: drop_sysctl_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void drop_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffe0002dfcc0)
Location: fs/proc/proc_sysctl.c:1647
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:put_links
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffe0002dfcc0-ffffffe0002dfef2: drop_sysctl_table (STB_LOCAL)
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
void drop_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81375ec0)
Location: fs/proc/proc_sysctl.c:1647
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:put_links
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff81375ec0-ffffffff8137606b: drop_sysctl_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void drop_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81366990)
Location: fs/proc/proc_sysctl.c:1647
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:put_links
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff81366990-ffffffff81366b3b: drop_sysctl_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void drop_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81373990)
Location: fs/proc/proc_sysctl.c:1647
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:put_links
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff81373990-ffffffff81373b3b: drop_sysctl_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void drop_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81386f20)
Location: fs/proc/proc_sysctl.c:1647
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:put_links
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff81386f20-ffffffff813870de: drop_sysctl_table (STB_LOCAL)
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
