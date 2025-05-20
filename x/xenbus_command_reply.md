# Function: <code>xenbus_command_reply</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xenbus_command_reply(struct xenbus_file_priv *u, unsigned int msg_type, const char *reply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8154d670)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:305
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
**Symbols:**

```
ffffffff8154d670-ffffffff8154d744: xenbus_command_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xenbus_command_reply(struct xenbus_file_priv *u, unsigned int msg_type, const char *reply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81561610)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:401
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
**Symbols:**

```
ffffffff81561610-ffffffff81561734: xenbus_command_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xenbus_command_reply(struct xenbus_file_priv *u, unsigned int msg_type, const char *reply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff815c5da0)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:401
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
**Symbols:**

```
ffffffff815c5da0-ffffffff815c5eca: xenbus_command_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xenbus_command_reply(struct xenbus_file_priv *u, unsigned int msg_type, const char *reply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff815fe4a0)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:401
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
**Symbols:**

```
ffffffff815fe4a0-ffffffff815fe665: xenbus_command_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xenbus_command_reply(struct xenbus_file_priv *u, unsigned int msg_type, const char *reply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81619570)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:401
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
**Symbols:**

```
ffffffff81619570-ffffffff81619735: xenbus_command_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xenbus_command_reply(struct xenbus_file_priv *u, unsigned int msg_type, const char *reply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8164d2b0)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:404
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
**Symbols:**

```
ffffffff8164d2b0-ffffffff8164d474: xenbus_command_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xenbus_command_reply(struct xenbus_file_priv *u, unsigned int msg_type, const char *reply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8166f7a0)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:419
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
**Symbols:**

```
ffffffff8166f7a0-ffffffff8166f964: xenbus_command_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xenbus_command_reply(struct xenbus_file_priv *u, unsigned int msg_type, const char *reply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8171fb90)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:419
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_transaction
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_transaction
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_transaction
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_transaction
```
**Symbols:**

```
ffffffff8171fb90-ffffffff8171fd61: xenbus_command_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xenbus_command_reply(struct xenbus_file_priv *u, unsigned int msg_type, const char *reply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8173caf0)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:419
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_transaction
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_transaction
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_transaction
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_transaction
```
**Symbols:**

```
ffffffff8173caf0-ffffffff8173ccc1: xenbus_command_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xenbus_command_reply(struct xenbus_file_priv *u, unsigned int msg_type, const char *reply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81720650)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:419
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_transaction
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_transaction
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_transaction
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_transaction
```
**Symbols:**

```
ffffffff81720650-ffffffff8172083c: xenbus_command_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xenbus_command_reply(struct xenbus_file_priv *u, unsigned int msg_type, const char *reply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8179f470)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:419
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_transaction
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_transaction
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_transaction
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_transaction
```
**Symbols:**

```
ffffffff8179f470-ffffffff8179f65c: xenbus_command_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xenbus_command_reply(struct xenbus_file_priv *u, unsigned int msg_type, const char *reply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff818d8ef0)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:419
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_transaction
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_transaction
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_transaction
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_transaction
```
**Symbols:**

```
ffffffff818d8ef0-ffffffff818d90c1: xenbus_command_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xenbus_command_reply(struct xenbus_file_priv *u, unsigned int msg_type, const char *reply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81a2b980)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:419
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_transaction
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_transaction
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_transaction
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_transaction
```
**Symbols:**

```
ffffffff81a2b980-ffffffff81a2bb51: xenbus_command_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xenbus_command_reply(struct xenbus_file_priv *u, unsigned int msg_type, const char *reply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81a75120)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:419
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_transaction
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_transaction
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_transaction
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_transaction
```
**Symbols:**

```
ffffffff81a75120-ffffffff81a752f1: xenbus_command_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xenbus_command_reply(struct xenbus_file_priv *u, unsigned int msg_type, const char *reply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81ac72b0)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:419
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_transaction
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_transaction
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_transaction
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_transaction
```
**Symbols:**

```
ffffffff81ac72b0-ffffffff81ac7481: xenbus_command_reply (STB_LOCAL)
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
int xenbus_command_reply(struct xenbus_file_priv *u, unsigned int msg_type, const char *reply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffff80001083a2f0)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:419
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
**Symbols:**

```
ffff80001083a2f0-ffff80001083a448: xenbus_command_reply (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int xenbus_command_reply(struct xenbus_file_priv *u, unsigned int msg_type, const char *reply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81635860)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:419
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
**Symbols:**

```
ffffffff81635860-ffffffff81635a24: xenbus_command_reply (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int xenbus_command_reply(struct xenbus_file_priv *u, unsigned int msg_type, const char *reply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff816635e0)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:419
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
**Symbols:**

```
ffffffff816635e0-ffffffff816637a4: xenbus_command_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xenbus_command_reply(struct xenbus_file_priv *u, unsigned int msg_type, const char *reply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8167dba0)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:419
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
**Symbols:**

```
ffffffff8167dba0-ffffffff8167dd64: xenbus_command_reply (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
