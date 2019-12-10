# Introduction

**GitBook** is a modern static site generator that provides a way to write and share books online. With Gitbook, teams can document everything from products to internal knowledge-bases and APIs.

## Gitbook V.S. LaTex Based Editors

While there are many available online LaTex based editors for collaborative documentation, such as [Overleaf](https://github.com/JingyaXun/gitbook/tree/137069765cbce8ae0b5f1005b1ac228b6579c3d7/introduction-to-gitbook/www.overleaf.com) and Google's [Docx2Latex](https://gsuite.google.com/marketplace/app/docx2latex/415272416461?pann=cwsdp&hl=en), we choose to use Gitbook because it offers easy version and access control. The most notable advantage aside from that is its flexibility of output formats. You can render to ePub, webpages, [PDF](https://github.com/GitbookIO/gitbook-pdf) etc. In comparison, LaTex based editors are relatively fixed to pdf.

We have summarized Gitbook's distinctive features into the following points. 

* \*\*\*\*[**Asynchronous Collaboration**](introduction.md#asynchronous-collaboration)\*\*\*\*
* \*\*\*\*[**Version Control**](introduction.md#version-control)\*\*\*\*
* \*\*\*\*[**Access Control** ](introduction.md#access-control)
* \*\*\*\*[**Get** **shareable** L**ink**](introduction.md#get-shareable-link)\*\*\*\*
* \*\*\*\*[**Embed Rich Contents**](introduction.md#embed-rich-contents)

### A**synchronous Collaboration**

You can collaborate asynchronously with your teammates by adding collaborators through the online Gitbook editor. Members of the team can exchange thoughts through the comment sections and review drafts before publishing. 

### Version Control

You can create backup for all your contents by integrating your Gitbook account with Github. With Github you can view the team's edit history and revert back to any version needed.    
  
Here is an example of adding Github integration:  
1. In your Github account, create new empty Github repository called _My Gitbook_  
2. In your Gitbook console, click on the `Integrations` icon on the left tool bar and turn on Github integration.   
3. Select `Edit Configuration` -&gt; `Sync Master Branch Only` -&gt; import the _My Gitbook_ repo you just created.   
4. Now you  can save all your online edits to Github!

### **Access Control** 

Once you added collaborators to your book, you can start access control by granting/removing team member's access to individual workspace. This is a great feature to foster large-scale team collaboration because you can divide work into sections and only assign each team the relevant sections to work on. 

### **Get** **shareable** L**ink** 

You can generate shareable link to allow non-Gitbook users to access your contents. Every time when someone access the link, the newest saved version of your book will be fetched and rendered. The link also will not expire as long as you have your book saved on an active Gitbook account. 

[Click here](https://jxun.gitbook.io/gitbook-user-guide/) to view this book through the shareable link we generated. 

### **Embed Rich Contents** 

Unlike traditional LaTex-based editors, Gitbook evolves with the changing styles of modern documentation by provide users with easy ways to embed in their book various forms of contents such as Youtube video, Github code, articles, etc. This allows people to create more interactive contents. 



  
  
  







## Further Reading

* [Publish Your Book Online with GitBook](https://medium.com/@rebeccapeltz/publish-your-book-online-with-gitbook-fc0ce9b7f12)
* [GitBook PDF Generator](https://github.com/GitbookIO/gitbook-pdf)

