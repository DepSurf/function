# Function: <code>__af4list_valid_rcu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff8180c55a)
Location: net/netlabel/netlabel_addrlist.h:84
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8180d72d)
Location: net/netlabel/netlabel_addrlist.h:84
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff8180ea46)
Location: net/netlabel/netlabel_addrlist.h:84
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff8187ef4f)
Location: net/netlabel/netlabel_addrlist.h:84
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8187fb83)
Location: net/netlabel/netlabel_addrlist.h:84
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818810c6)
Location: net/netlabel/netlabel_addrlist.h:84
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff818b37ff)
Location: net/netlabel/netlabel_addrlist.h:84
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818b4433)
Location: net/netlabel/netlabel_addrlist.h:84
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818b5976)
Location: net/netlabel/netlabel_addrlist.h:84
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff818da1c3)
Location: net/netlabel/netlabel_addrlist.h:84
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff818dae52)
Location: net/netlabel/netlabel_addrlist.h:84
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818dc283)
Location: net/netlabel/netlabel_addrlist.h:84
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff8195fdb3)
Location: net/netlabel/netlabel_addrlist.h:84
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81960a32)
Location: net/netlabel/netlabel_addrlist.h:84
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81961e73)
Location: net/netlabel/netlabel_addrlist.h:84
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff819b9573)
Location: net/netlabel/netlabel_addrlist.h:84
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819ba1d2)
Location: net/netlabel/netlabel_addrlist.h:84
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819bb637)
Location: net/netlabel/netlabel_addrlist.h:84
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff819f0843)
Location: net/netlabel/netlabel_addrlist.h:84
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f1b22)
Location: net/netlabel/netlabel_addrlist.h:84
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f28b7)
Location: net/netlabel/netlabel_addrlist.h:84
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81a5fae5)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a60875)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a61be1)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81a96715)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a974a5)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a987c1)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81b91da5)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b933c7)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b93ee1)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_condremove_iface
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81ba1a95)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81ba3017)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81ba3b46)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_condremove_iface
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81b90b75)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81b92137)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b92c66)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81c5d315)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81c5e8d7)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81c5f406)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81dff28e)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81e00b06)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81e017e4)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81fd3f4e)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81fd5956)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81fd6674)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff8204fb9e)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8205155a)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff82052334)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff8212224e)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff82123d2a)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listentry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff82124b24)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffff800010d658c4)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_mgmt.c (ffff800010d66964)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffff800010d67f74)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (c0e64280)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_mgmt.c (c0e64fe0)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (c0e666d8)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (c000000000ea18d8)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_mgmt.c (c000000000ea2bec)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (c000000000ea4958)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffe000899580)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_mgmt.c (ffffffe00089a33a)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffe00089b3d0)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81a35aa5)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81a36835)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a37b51)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff819f26c5)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff819f3455)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f4771)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81aa1955)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aa26e5)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aa3a01)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81aadc9e)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81aaea55)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aafe26)
Location: net/netlabel/netlabel_addrlist.h:70
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlistdef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
</details>
</li>
</ul>

## Differences
