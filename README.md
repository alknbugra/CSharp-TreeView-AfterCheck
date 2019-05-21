# CSharp-TreeView-AfterCheck
```sh
private void treeView1_AfterCheck(object sender, TreeViewEventArgs e)
        {
            for (int i = 0; i < treeView1.Nodes.Count; i++)
            {
                if (treeView1.Nodes[i].Text == e.Node.FullPath)
                {
                    for (int l = 0; l < treeView1.Nodes[i].Nodes.Count; l++)
                    {
                        treeView1.Nodes[i].Nodes[l].Checked = true;
                    }
                }
            }
        }
```

![Ekran Alıntısı](https://user-images.githubusercontent.com/29266933/58074126-18f85f80-7bad-11e9-88b2-2ddc10aad0a4.PNG)
![Ekran Alıntısı_1](https://user-images.githubusercontent.com/29266933/58074128-1a298c80-7bad-11e9-9909-892eeb555ccd.PNG)
