
<style>



  /*--------------- view ---------------*/
  body[style],
  body[style*="background-color: white;"] {
    background-color: #444444 !important;

  }

  body {
    color: #abb2bf;
  }

}

  .ui-view-area,
  .markdown-body,
  .ui-content {
    background: #444444;
    color: #abb2bf;
  }



  h1,
  h2,
  h3,
  h4,
  h5,
  h6,
  p {
    color: #ddd;
  }

  hr {
    border-color: #6d6d6d;
  }

  /* form */
  .form-control {
    background: #333;
    color: #fff;

  }

  .form-control::placeholder,
  .form-control::-webkit-input-placeholder,
  .form-control:-moz-placeholder,
  .form-control::-moz-placeholder,
  .form-control:-ms-input-placeholder {
    color: #eee;
  }

  /*--------------- navbar ---------------*/
  .header {
    background-color: #0e0e0e;
    border-color: #0e0e0e;
  }

  .navbar {
    background-color: #0e0e0e;
    border-color: #0e0e0e;
  }

  .navbar a {
    color: #eee !important;
  }

  .navbar .btn-group label {
    background-color: #0e0e0e;
    color: #eee;
    border-color: #555;
  }

  .navbar .btn-group label.btn-default:focus,
  .navbar .btn-group label.btn-default:hover {
    background-color: #2a2a2a;
    color: #eee;
    border-color: #555;
  }


  .navbar .btn-group label.active {
    background-color: #555;
    color: #eee;
    border-color: #555;
  }

  .navbar .btn-group label.active:focus,
  .navbar .btn-group label.active:hover {
    background-color: #555;
    color: #eee;
    border-color: #555;
  }

  .navbar-default .btn-link:focus,
  .navbar-default .btn-link:hover {
    color: #eee;
  }

  .navbar-default .navbar-nav>.open>a,
  .navbar-default .navbar-nav>.open>a:focus,
  .navbar-default .navbar-nav>.open>a:hover {
    background-color: #555;
  }

  .dropdown-header {
    color: #aaa;
  }

  .dropdown-menu {
    background-color: #222;
    border: 1px solid #555;
    border-top: none;
  }

  .dropdown-menu>li>a {
    color: #eee;
  }

  .dropdown-menu>li>a:focus,
  .dropdown-menu>li>a:hover {
    background-color: #555555;
    color: #eee;
  }

  .dropdown-menu .divider {
    background-color: #555;
  }

  .header .open .dropdown-menu {
    background-color: #202020;
  }

  .navbar .announcement-popover {
    background: #4F4F4F;
  }

  .navbar .announcement-popover .announcement-popover-header {
    background: #2e2e2e;
    border-bottom: 1px solid #2e2e2e;
  }

  .navbar .announcement-popover .announcement-popover-body {
    background: #4F4F4F;
    color: #eee;
  }

  .navbar .announcement-popover .announcement-popover-footer {
    background: #4F4F4F;
  }

  .navbar .announcement-area .caption.inverse {
    color: #eee;
  }

  .label-warning {
    background-color: #ffc107;
    color: #212529;
  }

  /*--------------- history / recent ---------------*/
  .list.row-layout li .item {
    border-color: #696c7d;
  }

  .list.row-layout li:nth-last-of-type(1) .item {
    border-bottom: none;
  }

  .list li .item {
    background: #1c1c1c;
  }

  .list li:hover .item,
  .list li:focus .item {
    background: #404040;
  }

  .list li .item h4 {
    color: #fff;
  }

  .list li p {
    color: #ccc;
  }

  .list li p i {
    font-style: normal;
  }

  .list li .item .content .tags span {
    background: #555;
  }

  .list li .item.wide .content .title a,
  .list li .item.wide .content .title a:focus,
  .list li .item.wide .content .title a:hover {
    color: #ddd;
  }

  .ui-item {
    color: #fff;
    opacity: 0.7;
  }

  .ui-item:hover,
  .ui-item:focus {
    opacity: 1;
    color: #fff;
  }

  .list li .item.wide hr {
    border-color: #6d6d6d;
  }

  .overview-widget-group .btn,
  .multi-select-dropdown-menu .ui-dropdown-label,
  .multi-select-dropdown-menu .dropdown-options,
  .form-control {
    border-color: #6d6d6d;
  }

  .multi-select-dropdown-menu .dropdown-options .ui-option:hover {
    background-color: #4d4d4d;
    color: #eee;
  }

  #overview-control-form #overview-keyword-input-container .select2-container {
    background-color: #3e4045 !important;
  }

  #overview-control-form #overview-keyword-input-container .select2-container .select2-choices {
    background-color: #3e4045;
  }

  .search {
    background-color: #3e4045;
    color: #eee;
  }

  .btn.btn-gray {
    background: #1b1b1b;
  }

  .btn.btn-gray:hover {
    background: #4d4d4d;
    color: #eee;
  }

  .search::placeholder,
  .search::-webkit-input-placeholder,
  .search:-moz-placeholder,
  .search::-moz-placeholder,
  .search:-ms-input-placeholder {
    color: #eee;
  }

  .btn.btn-gray {
    border-color: #6d6d6d;
    background: #333;
    color: #eee;
  }

  .select2-default {
    color: #eee !important;
  }

  .select2-results .select2-highlighted {
    background: #4d4d4d;
    color: #eee;
  }

  .select2-container-multi .select2-choices {
    background: #3e4045;
  }

  .select2-container-multi .select2-choices .select2-search-choice {
    background: #131313;
    color: #eee;
    border-color: #555;
    box-shadow: none;
  }

  .btn-default,
  .btn-default:focus {
    color: #eee;
    background-color: #2e2e2e;
    border-color: #6a6a6a;
  }

  .btn-default.active.focus,
  .btn-default.active:focus,
  .btn-default.active:hover,
  .btn-default:active.focus,
  .btn-default:active:focus,
  .btn-default:active:hover,
  .open>.dropdown-toggle.btn-default.focus,
  .open>.dropdown-toggle.btn-default:focus,
  .open>.dropdown-toggle.btn-default:hover {
    background: #737373;
  }

  .btn-default:hover {
    color: #fff;
    background-color: #7d7d7d;
    border-color: #6a6a6a;
  }

  .overview-widget-group .btn.active {
    background-color: #6a6a6a;
    color: #eee;
  }

  .overview-widget-group .btn:hover {
    background-color: #7d7d7d;
    color: #eee;
    border-color: #636363;
  }

  .overview-widget-group .slider.round {
    border-color: #ccc;
  }

  .overview-widget-group .slider.round:before {
    border-color: #ccc;
  }

  .overview-widget-group input:checked+.slider {
    background-color: #ccc;
  }

  .ui-category-description-icon a {
    color: #eee;
  }

  .item .ui-history-pin.active {
    color: #f00;
  }

  .ui-history-close {
    color: #eee;
    opacity: 0.5;
  }

  .pagination>li>a,
  .pagination>li>span {
    color: #eee;
    background-color: #2e2e2e;
    border-color: #6a6a6a;
  }

  .pagination>li>a:hover {
    color: #fff;
    background-color: #7d7d7d;
    border-color: #6a6a6a;
  }

  .pagination>.disabled>a,
  .pagination>.disabled>a:focus,
  .pagination>.disabled>a:hover,
  .pagination>.disabled>span,
  .pagination>.disabled>span:focus,
  .pagination>.disabled>span:hover {
    color: #eee;
    background-color: #2e2e2e;
    border-color: #6a6a6a;
  }

  .pagination.dark>li>a,
  .pagination.dark>li>span {
    color: #aaa;
  }

  /*--------------- settings ---------------*/
  .section .form-horizontal .form-group .btn-default {
    font-size: 16px;
    border-color: #6d6d6d;
    background-color: #333;
    color: #FFF;
  }

  .section .form-horizontal .form-group .btn-default:hover,
  .section .form-horizontal .form-group .btn-default:focus {
    background-color: #737373;
    color: #FFF;
  }

  .section .form-horizontal .form-control:focus {
    border-color: #bbb;
  }

  /*--------------- share view ---------------*/
  #notificationLabel,
  .ui-infobar .btn.ui-edit {
    color: #eee;
    border-color: #6a6a6a;
  }

  .ui-infobar__user-info li {
    color: #bbb;
  }

  footer {
    background: #101010;
    color: #bbb;
    border-top: 1px solid #454545;
  }

  footer a {
    color: #bbb;
  }

  /*--------------- doc view ---------------*/
  .markdown-body h1,
  .markdown-body h2,
  .markdown-body h3,
  .markdown-body h4,
  .markdown-body h5,
  .markdown-body h6,
  .markdown-body hr,
  #doc>h1 {
    color: #ddd;
    border-color: #777 !important;
  }

  .h1 .small,
  .h1 small,
  .h2 .small,
  .h2 small,
  .h3 .small,
  .h3 small,
  .h4 .small,
  .h4 small,
  .h5 .small,
  .h5 small,
  .h6 .small,
  .h6 small,
  h1 .small,
  h1 small,
  h2 .small,
  h2 small,
  h3 .small,
  h3 small,
  h4 .small,
  h4 small,
  h5 .small,
  h5 small,
  h6 .small,
  h6 small {
    color: #ddd;
  }

  .markdown-body p {
    color: #ddd;
  }

  .markdown-body a {
    color: #7bf;
  }

  .markdown-body a code {
    color: #7bf !important;
  }

  .markdown-body ul li,
  .markdown-body ol li {
    color: #ddd;
  }

  .markdown-body blockquote {
    color: #ddd;
    border-left-color: #777;
    font-size: 16px;
  }

  <--.markdown-body code,
  code {
    color: #dfdfdf !important;
    background-color: #424a55;
  }-->

  .markdown-body pre {
    background-color: #1e1e1e;
    border: 1px solid #555 !important;
    color: #dfdfdf;
  }

  blockquote .small,
  blockquote footer,
  blockquote small {
    color: #bbb;
  }

  .mark,
  mark {
    background-color: rgba(255, 255, 0, 0.32) !important;
    color: #ddd;
    margin: .1em;
    padding: .1em .2em;
  }

  /* Todo list */
  .task-list-item-checkbox {
    margin: 0.18em 0 0.2em -1.3em !important;
  }

  .task-list-item input[type=checkbox] {
    -webkit-appearance: none;
    -moz-appearance: none;
    appearance: none;
    position: relative;
    top: -1px;
    margin: 0 1rem 0 0;
    cursor: pointer;
  }

  .task-list-item input[type=checkbox]::before {
    -webkit-transition: all 0.1s ease-in-out;
    -moz-transition: all 0.1s ease-in-out;
    transition: all 0.1s ease-in-out;
    content: "";
    position: absolute;
    left: 0;
    z-index: 1;
    width: 16px;
    height: 16px;
    border: 2px solid #F44336;
  }

  .task-list-item input[type=checkbox]:checked::before {
    -webkit-transform: rotate(-48deg);
    -moz-transform: rotate(-48deg);
    -ms-transform: rotate(-48deg);
    -o-transform: rotate(-48deg);
    transform: rotate(-48deg);
    height: 9px;
    border-color: #00E676;
    border-top-style: none;
    border-right-style: none;
  }

  .task-list-item input[type=checkbox]::after {
    content: "";
    position: absolute;
    top: -0.125rem;
    left: 0;
    width: 16px;
    height: 16px;
    background: #333;
    cursor: pointer;
  }

  /* table */
  .markdown-body table tr {
    background-color: #1e1e1e;
    border-top: none;
    border-bottom: 1px solid rgba(255, 255, 255, 0.3);
  }

  .markdown-body table tr:first-child {
    border-top: 1px solid rgba(255, 255, 255, 0.2);
  }

  .markdown-body table tr:nth-child(2n) {
    background-color: #333;
  }

  .markdown-body table tr th {
    color: #64B5F6;
  }

  .markdown-body table th,
  .markdown-body table td {
    border: none;
  }

  .markdown-body table tr th:first-child,
  .markdown-body table tr td:first-child {
    border-left: 1px solid rgba(255, 255, 255, 0.1);
  }

  .markdown-body table tr th:last-child,
  .markdown-body table tr td:last-child {
    border-right: 1px solid rgba(255, 255, 255, 0.1);
  }

  .markdown-body table tr td {
    color: #ddd;
  }



  .markdown-body pre.flow-chart,
  .markdown-body pre.sequence-diagram,
  .markdown-body pre.graphviz,
  .markdown-body pre.mermaid,
  .markdown-body pre.abc {
    background-color: #1e1e1e;
    color: #ddd;



  }
              .markdown-body pre.gri {
                stroke: lightgrey;
                opacity: 0.3;
                shape-rendering: crispEdges;
            }
            .markdown-body pre.grid path {
                stroke-width: 0;
            }
  


  /* alert */
  .alert h1,
  .alert h2,
  .alert h3,
  .alert h4,
  .alert h5,
  .alert h6,
  .alert p,
  .alert ul li,
  .alert ol li {
    color: #31708f;
  }

  .alert a {
    color: #002752;
    font-weight: 700;
  }

  .alert h1:first-child,
  .alert h2:first-child,
  .alert h3:first-child,
  .alert h4:first-child,
  .alert h5:first-child,
  .alert h6:first-child {
    margin-top: 0;
  }

  .markdown-body .alert>p {
    margin-top: 0px;
    margin-bottom: 10px;
  }

  .markdown-body .alert>ul,
  .markdown-body .alert>ol {
    margin-bottom: 16px;
  }

  .markdown-body .alert>*:last-child {
    margin-bottom: 0;
  }

  .alert-warning {
    background-color: #fff3cd;
    border-color: #ffeeba;
  }

  /* scroll bar */
  .ui-edit-area .ui-resizable-handle.ui-resizable-e {
    background-color: #303030;
    border: 1px solid #303030;
    box-shadow: none;
  }

  /* info bar */
  .ui-infobar {
    color: #999;
  }

  /* permission */
  .permission-popover-btn-group .btn.focus,
  .permission-popover-btn-group .btn:active,
  .permission-popover-btn-group .btn:focus,
  .permission-popover-btn-group .btn.active {
    background-color: #6a6a6a !important;
    color: #eee !important;
    border-color: #555 !important;
  }

  .permission-popover-btn-group .btn:hover,
  .permission-popover-btn-group .btn.active:hover {
    background-color: #7d7d7d !important;
    color: #eee !important;
    border-color: #636363 !important;
  }

  .ui-delete-note a:hover,
  .ui-delete-note a:focus,
  .ui-delete-note a:active {
    background-color: #dc3545 !important;
  }

  .ui-invitee-invite {
    border-color: #6a6a6a !important;
  }

  .ui-invitee-invite:hover,
  .ui-invitee-invite:focus {
    background-color: #737373;
    color: #eee !important;
  }

  .ui-invitee.ui-invitee-list .ui-invitee-remove,
  .ui-invitee.ui-invitee-list .ui-invitee-remove:hover,
  .ui-invitee.ui-invitee-list .ui-invitee-remove:focus,
  .ui-invitee.ui-invitee-list .ui-invitee-remove:active {
    background-color: #dc3545;
    border: 1px solid #dc3545;
  }

  .select2-container {
    background: #202020;
  }

  .select2-container-multi .select2-choices .select2-search-field input {
    color: #eee;
  }

  .select2-container-multi .select2-choices .select2-search-field input.select2-active {
    color: #000;
  }

  .select2-drop {
    background: #202020;
    color: #eee;
  }

  .select2-results .select2-no-results,
  .select2-results .select2-searching,
  .select2-results .select2-ajax-error,
  .select2-results .select2-selection-limit {
    background: #202020;
  }

  /* table of contents block*/
  .ui-toc-dropdown {
    width: 42vw;
    max-height: 90vh;
    overflow: auto;
    text-align: inherit;
  }

  /* table of contents text*/
  .ui-toc-dropdown .nav>li>a {
    font-size: 14px;
    font-weight: bold;
    color: #ddd;
  }

  /* table of contents text: active*/
  .ui-toc-dropdown .nav>.active:focus>a,
  .ui-toc-dropdown .nav>.active:hover>a,
  .ui-toc-dropdown .nav>.active>a {
    color: #7bf;
    border-left-color: #7bf;
  }

  /* table of contents text: focus, hover*/
  .ui-toc-dropdown .nav>li>a:focus,
  .ui-toc-dropdown .nav>li>a:hover {
    color: #7bf;
    border-left-color: #7bf;
  }

  /* drop down floating table of contents */
  .ui-toc-dropdown.dropdown-menu {
    background: #333;
  }

  .toc-menu a {
    color: #ddd;
  }

  .toc-menu a:focus,
  .toc-menu a:hover {
    color: #7bf;
  }


  /*--------------- editor ---------------*/
  .cm-m-markdown {
    color: #ddd;
  }

  .cm-s-one-dark .cm-header,
  .cm-m-xml.cm-attribute {
    color: #ffa653;
  }

  .cm-s-one-dark .cm-string,
  .cm-s-one-dark .cm-variable-2 {
    color: #7bf;
  }

  .cm-m-markdown.cm-variable-3 {
    color: #ff7e7e;
  }

  .cm-s-one-dark .cm-link {
    color: #b0ee83;
  }

  .cm-s-one-dark .CodeMirror-linenumber {
    color: #666;
  }

  .cm-strong {
    color: #f4511e;
  }

  .cm-s-one-dark .cm-comment {
    color: #a9a9a9;
  }

  .cm-matchhighlight {
    color: #ffea00;
  }

  .cm-positive {
    color: #11bf64;
  }

  .cm-negative {
    color: #ff3e3e;
  }

  .dropdown-menu.CodeMirror-other-cursor {
    border: 2px solid #4d4d4d;
    background-color: #202020;
  }

  .dropdown-menu.CodeMirror-other-cursor li a {
    color: #ececec;
  }

  /*--------------- book mode ---------------*/
  .topbar {
    background: #1e1e1e;
  }

  .btn.focus,
  .btn:focus,
  .btn:hover {
    color: #aaa;
  }

  .summary {
    background: #1e1e1e;
  }

  .summary,
  .toolbar {
    background: #1e1e1e !important;
    border-color: #4d4d4d !important;
  }

  .toolbar i {
    color: #fff;
  }

  .summary h1,
  .summary h2,
  .summary h3 .summary hr {
    color: #ddd;
    border-color: #777 !important;
  }

  .summary .nav>li>a {
    color: #7bf;
  }

  .summary .nav-pills>li.active>a,
  .summary .nav-pills>li.active>a:focus,
  .summary .nav-pills>li.active>a:hover {
    color: #ff9100;
  }

  .ui-summary-search {
    font-size: 16px;
    border: 1px solid #6D6D6D;
    background-color: #333;
    color: #FFF;
  }

  .summary h1,
  .summary h2,
  .summary h3,
  .summary h4,
  .summary h5,
  .summary h6 {
    border-color: #454545;
  }

  /* fix body background color to dark */
  div[class$=container-mask] {
    background: #1e1e1e;
    z-index: 1;
    display: block;
  }

  /* notification */
  .dropdown.ui-notification .ui-notification-label,
  .dropdown.ui-invitee .ui-invitee-label {
    color: #eee;
    border-color: #6a6a6a;
  }

  .ui-notification .dropdown-menu {
    border-top: 1px solid #555;
  }

  /*--------------- help ---------------*/
  .modal-header {
    background-color: #2a2a2a;
  }

  .panel-default {
    border-color: #6d6d6d;
  }

  .panel-default>.panel-heading {
    background-color: #2a2a2a;
    color: #eee;
    border-color: #6d6d6d;
  }

  .panel-body {
    background: #2e2e2e;
  }

  .panel-body a {
    color: #7bf;
  }

  .table>tbody>tr>td,
  .table>tbody>tr>th,
  .table>tfoot>tr>td,
  .table>tfoot>tr>th,
  .table>thead>tr>td,
  .table>thead>tr>th {
    border-color: #6d6d6d;
  }

  /*--------------- comment ---------------*/
  .ui-comment-container .ui-comment-header {
    background-color: #2a2a2a;
    color: #eee;
    border-color: #6d6d6d;
  }

  .ui-comment-container {
    background-color: #2e2e2e;
    border-color: #6d6d6d;
  }

  .ui-comment-container .ui-comments-container .ui-comment .comment-author {
    color: #eee;
  }

  .ui-comment-container .ui-comments-container .ui-comment .timestamp {
    color: #aaa;
  }

  .ui-comment-container .ui-comments-container .ui-comment .comment-content {
    color: #eee;
  }

  .ui-comment-container .ui-comments-container .ui-comment .comment-menu {
    color: #eee;
  }

  .ui-comment-container .ui-comments-container .ui-comment .comment-menu .comment-dropdown-menu {
    background: #222;
    color: #eee;
    border-color: #555;
  }

  .ui-comment-container .ui-comments-container .ui-comment .comment-menu .comment-dropdown-menu>div:hover {
    background-color: #555555;
    color: #eee;
  }

  .ui-comment-container .ui-comments-container .ui-comment .comment-menu:hover,
  .ui-comment-container .ui-comments-container .ui-comment .comment-menu:active,
  .ui-comment-container .ui-comments-container .ui-comment .comment-menu.active {
    background-color: #737373;
    color: #eee;
  }

  .ui-comment-container .ui-comment-input-container {
    background-color: #3c3c3c;
  }

  .ui-comment-container textarea {
    background-color: #3e4045;
    color: #eee;
    border: 1px solid #6d6d6d;
  }

  .ui-comment-container textarea::placeholder,
  .ui-comment-container textarea::-webkit-input-placeholder,
  .ui-comment-container textarea:-moz-placeholder,
  .ui-comment-container textarea::-moz-placeholder,
  .ui-comment-container textarea:-ms-input-placeholder {
    color: #eee;
  }

  @keyframes highlight {
    0% {
      background-color: #3c3c3c;
    }

    30% {
      background-color: #3c3c3c;
    }

    100% {
      background-color: transparent;
    }
  }

  /*--------------- template ---------------*/
  .template-content .modal-header {
    background: #2a2a2a;
  }

  .template-content .close {
    color: #fff;
  }

  .template-content .modal-title {
    color: #eee;
  }

  .template-content .ui-templates-container {
    border-color: #6d6d6d;
  }

  .ui-templates-container .ui-create-template-btn {
    background: #446fab;
    color: #fff;
  }

  .ui-template-list-filter .ui-template-list-filter-label,
  .ui-template-list-filter .ui-template-list-filter-label:hover {
    color: #eee;
  }

  .ui-template-list .list-group-item.active {
    background: #4d4d4d;
  }

  .ui-template-list .list-group-item.active:focus {
    background: #4d4d4d !important;
  }

  .list-group-item.active,
  .list-group-item.active:focus,
  .list-group-item.active:hover {
    color: #eee;
  }

  .ui-template-list .list-group-item .list-group-item-heading {
    color: #eee;
  }

  .ui-template-list .list-group-item.active .list-group-item-heading {
    color: #eee;
  }

  .ui-template-list .list-group-item:hover {
    background: #4d4d4d !important;
  }

  .ui-template-item-menu {
    color: #eee !important;
  }

  .ui-template-list .list-group-item {
    color: #fff;
  }

  .ui-template-list .list-group-item .dropdown-container.open {
    background-color: #2a2a2a;
  }

  .ui-template-list .list-group-item .dropdown-container:hover {
    background-color: #2a2a2a !important;
  }

  .template-menu .more-template {
    border-color: #6d6d6d;
  }

  .template-menu .more-template:hover {
    color: #eee;
    border-color: #6d6d6d;
  }

  /*--------------- code mirror ---------------*/
  .modal-content {
    background: #1f2226;
  }

  .modal-header {
    border-bottom: 1px solid #46484f;
  }

  .modal-footer {
    border-top: 1px solid #46484f;
  }

  a.list-group-item {
    background: #1f2226;
    color: #ddd;
    border: 1px solid #46484f;
  }

  a.list-group-item .list-group-item-heading {
    color: #ddd;
  }

  a.list-group-item:focus,
  a.list-group-item:hover {
    background: #434651;
    color: #ddd;
  }

  button.close {
    color: #ddd;
    opacity: .5;
  }

  .close:focus, .close:hover {
    color: #fff;
    opacity: .8;
  }

  .CodeMirror {
    background: #1f2226;
  }

  .CodeMirror-gutters {
    background: #1f2226;
    border-right: 1px solid rgba(204, 217, 255, 0.1);
  }

  .cm-s-default .cm-comment {
    color: #888;
  }

  .cm-s-default .cm-quote {
    color: #ddd;
  }

  .cm-s-default .cm-header {
    color: #ffa653;
  }

  .cm-s-default .cm-link {
    color: #b0ee83;
  }

  .cm-s-default .cm-string,
  .cm-s-default .cm-variable-2 {
    color: #7bf;
  }

  .cm-s-default .cm-def {
    color: #c678dd;
  }

  .cm-s-default .cm-number,
  .cm-s-default .cm-attribute,
  .cm-s-default .cm-qualifier,
  .cm-s-default .cm-plus,
  .cm-s-default .cm-atom {
    color: #eda35e;
  }

  .cm-s-default .cm-property,
  .cm-s-default .cm-variable,
  .cm-s-default .cm-variable-3,
  .cm-s-default .cm-operator,
  .cm-s-default .cm-bracket {
    color: #f76e79;
  }

  .cm-s-default .cm-keyword,
  .cm-s-default .cm-builtin,
  .cm-s-default .cm-tag {
    color: #98c379;
  }

  .modal-title {
    color: #ccc;
  }

  .modal-body {
    color: #ccc !important;
  }

  div[contenteditable]:empty:not(:focus):before {
    color: #aaa;
  }

  .CodeMirror pre {
    color: #ddd;
  }

  .CodeMirror pre span[style^="background-color: rgb(221, 251, 230)"] {
    background-color: #288c27 !important;
  }

  .CodeMirror pre span[style^="background-color: rgb(249, 215, 220)"] {
    background-color: #a52721 !important;
  }

  /*------- code highlight: Visual Stutdio Code theme for highlight.js -------*/
  .hljs {
    background: #1E1E1E;
    color: #DCDCDC;
  }

  .hljs-keyword,
  .hljs-literal,
  .hljs-symbol,
  .hljs-name {
    color: #569CD6;
  }

  .hljs-link {
    color: #569CD6;
    text-decoration: underline;
  }

  .hljs-built_in,
  .hljs-type {
    color: #4EC9B0;
  }

  .hljs-number,
  .hljs-class {
    color: #B8D7A3;
  }

  .hljs-string,
  .hljs-meta-string {
    color: #D69D85;
  }

  .hljs-regexp,
  .hljs-template-tag {
    color: #d16969;
  }

  .hljs-title {
    color: #dcdcaa;
  }

  .hljs-subst,
  .hljs-function,
  .hljs-formula {
    color: #DCDCDC;
  }

  .hljs-comment,
  .hljs-quote {
    color: #57A64A;
  }

  .hljs-doctag {
    color: #608B4E;
  }

  .hljs-meta,
  .hljs-meta-keyword,
  .hljs-tag {
    color: #9B9B9B;
  }

  .hljs-variable,
  .hljs-template-variable {
    color: #BD63C5;
  }

  .hljs-params,
  .hljs-attr,
  .hljs-attribute,
  .hljs-builtin-name {
    color: #9CDCFE;
  }

  .hljs-section {
    color: gold;
  }

  .hljs-emphasis {
    font-style: italic;
  }

  .hljs-strong {
    font-weight: bold;
  }

  /*
  .hljs-code {
    font-family:'Monospace';
  }
  */

  .hljs-bullet,
  .hljs-selector-tag,
  .hljs-selector-id,
  .hljs-selector-class,
  .hljs-selector-attr,
  .hljs-selector-pseudo {
    color: #D7BA7D;
  }

  .hljs-addition {
    background-color: #155a36;
    color: #dfdfdf;
    display: inline-block;
    width: 100%;
  }

  .hljs-deletion {
    background-color: #872e2e;
    color: #dfdfdf;
    display: inline-block;
    width: 100%;
  }

  /*---------- code highlight: Visual Stutdio Code theme for Prism.js ----------*/
  code[class*="language-"],
  pre[class*="language-"] {
    color: #DCDCDC;
  }

  :not(pre)>code[class*="language-"],
  pre[class*="language-"] {
    background: #1E1E1E;
  }

  .token.comment,
  .token.block-comment,
  .token.prolog,
  .token.cdata {
    color: #57A64A;
  }

  .token.doctype,
  .token.punctuation {
    color: #9B9B9B;
  }

  .token.tag,
  .token.entity {
    color: #569CD6;
  }

  .token.attr-name,
  .token.namespace,
  .token.deleted,
  .token.property,
  .token.builtin {
    color: #9CDCFE;
  }

  .token.function,
  .token.function-name {
    color: #dcdcaa;
  }

  .token.boolean,
  .token.keyword,
  .token.important {
    color: #569CD6;
  }

  .token.number {
    color: #B8D7A3;
  }

  .token.class-name,
  .token.constant {
    color: #4EC9B0;
  }

  .token.symbol {
    color: #f8c555;
  }

  .token.rule {
    color: #c586c0;
  }

  .token.selector {
    color: #D7BA7D;
  }

  .token.atrule {
    color: #cc99cd;
  }

  .token.string,
  .token.attr-value {
    color: #D69D85;
  }

  .token.char {
    color: #7ec699;
  }

  .token.variable {
    color: #BD63C5;
  }

  .token.regex {
    color: #d16969;
  }

  .token.operator {
    color: #DCDCDC;
    background: transparent;
  }

  .token.url {
    color: #67cdcc;
  }

  .token.important,
  .token.bold {
    font-weight: bold;
  }

  .token.italic {
    font-style: italic;
  }

  .token.entity {
    cursor: help;
  }

  .token.inserted {
    color: green;
  }

  /*---------- code highlight: dark theme for Gist ----------*/
  .gist .gist-file {
    border: 1px solid #555;
  }

  .gist .gist-data {
    background-color: #1e1e1e;
    border-bottom: 1px solid #555;
  }

  .gist .gist-meta {
    background-color: #424a55;
    color: #eee;
  }

  .gist .gist-meta a {
    color: #eee;
  }

  .gist .highlight {
    color: #eee;
    background-color: #1e1e1e;
  }

  .gist .blob-num {
    color: #afafaf;
  }

  .gist .blob-code-inner {
    color: #dfdfdf;
  }

  .pl-mb {
    color: #fff !important;
  }

  .pl-c {
    color: #57A64A !important;
  }

  /* comment */
  .pl-ent {
    color: #569CD6 !important;
  }

  /* entity */
  .pl-e {
    color: #9CDCFE !important;
  }

  .pl-en {
    color: #4EC9B0 !important;
  }

  /* entity attribute */
  .pl-smi {
    color: #9CDCFE !important;
  }

  .pl-k {
    color: #569cd6 !important;
  }

  .pl-c1,
  .pl-s .pl-v {
    color: #4EC9B0 !important;
  }

  .pl-pds,
  .pl-s,
  .pl-s .pl-pse .pl-s1,
  .pl-sr,
  .pl-sr .pl-cce,
  .pl-sr .pl-sra,
  .pl-sr .pl-sre,
  .pl-s .pl-s1 {
    color: #D69D85 !important;
  }

  .pl-s .pl-s1 .pl-pse {
    color: #c5dbff !important;
  }

  /* strings */
  .diff-table .pl-c,
  .diff-table .pl-ent,
  .diff-table .pl-e,
  .diff-table .pl-en,
  .diff-table .pl-pds,
  .diff-table .pl-s,
  .diff-table .pl-s .pl-s1,
  .diff-table .pl-s .pl-pse .pl-s1,
  .diff-table .pl-sr,
  .diff-table .pl-sr .pl-cce,
  .diff-table .pl-sr .pl-sra,
  .diff-table .pl-sr .pl-sre,
  .diff-table .pl-k,
  .diff-table .pl-smi,
  .diff-table .pl-c1,
  .diff-table .pl-v {
    color: #eee !important;
  }

 </style>



###### tags: `GoLang`

# GoLang 應用範例:

### Go 單元測試(Unit Test)介紹:
>
> #### go test 工具說明 :
> Golang 官方工具包提供單元測試功能透過，==`go test`== 進行單元測試:
> 
> > 1. 單元測試檔名必須以 ==`*_test.go`== 結尾命名，和被測試檔案必須在同一個包(package)中，此檔名內容僅會在 ==`go test`== 下執行。
> > 2. 單元測試函式必須是 ==`Test`== 或是 ==`Benchmark`== 作為函式開頭名稱後面第一字必需大寫 ex: **TestExample** 、**BenchmarkExample** 。
> > 3. 單元測試函式輸入參數型別必須 ==`*testing.T`== 、 ==`*testing.B`==
> >
> 
> ==`go test`== 工具附加命令參數設定值:
>    
> > ==`-c`== : 不運行測試，將go test編譯成為可執行檔案(二進位文件)。
> > 
> > ==`-i`==  : 不運行測試，安裝測試包依賴的package。
> > 
> > ==`-v`==  : 測試過程顯示列表所有函式(通過/不通過)。
> > 
> > ==`-short`==  : 縮短運行時間較長的測試項目。
> > 
> > ==`-args "-TT"`==  : 測試時置入命令參數 **-TT** (詳細參考flag.Args)
> > 
> > ==`-timeout 1h`==  : 如果測試用例運行時間超過 **1小時**，則拋出panic。
> > 
> > ==`-run=funcname`== : 僅測試函式包含名稱 **funcname** 。(預設值 ==`.`==，表示全部測試)
> > 
> > ==`-bench=funcname`== : 僅效能測試函式包含名稱 **funcname** 。(預設值 ==`.`==，表示全測試)
> > 
> > ==`-benchmem`==  : 設置效能測試的時顯示記憶體使用資訊。
> > 
> > ==`-benchtime 10s`==  : 設置效能測試運行的時間 **10秒** (預設值**1秒**)
> > 
> > ==`-parallel 4`==  : 設定效能測試並行最大CPU核心數為 **4** (預設值GOMAXPROCS)
> > 
> > ==`-cpu 1,2,3,4`==  : 效能測試會依序由 **1~4** CPU核心數測試。(預設值為GOMAXPROCS)
> > 
> > ==`-cpuprofile cpu.out`==  : 將測試過程CPU使用量紀錄儲存至 **cpu.out**
> > 
> > ==`-memprofile mem.out`==  : 將測試過程記憶體使用量紀錄儲存至 **mem.out**
> > 
> > ==`-blockprofile block.out`==  : 將測試過程中goroutine阻塞分析紀錄儲存至 **block.out**
> > 
> > ==`-blockprofilerate 2`== : 設置goroutine阻塞時候紀錄間隔時間為 **2納秒** (預設值**1納秒**)
> > 
> #### 單元測試關鍵點 :
> 
> 測試資料構造時要考慮這樣幾個方面：
> >**正常輸入**: 驗證函式的正常邏輯是否通過
> >**邊界輸入**: 驗證在極端情況下的輸入，函式是否在有相應的容錯處理
> >**非法輸入**: 對於一些非正常輸入，看函式是否引起函式的奔潰和資料洩露等問題
> >**白盒覆蓋**: 覆蓋到函式的所有程式碼，語句覆蓋、條件覆蓋、分支覆蓋、分支/條件覆蓋、條件組合覆蓋。
>
> 編寫原則與成本，效率權衡 :
> 
> > 1. 優先編寫核心元件和邏輯模組的測試用例。
> > 2. 邏輯類似的元件如果存在多個，優先編寫其中一種邏輯元件的測試用例。
> > 3. 發現Bug時一定先編寫測試用例進行Debug(保持更新測試用例)。
> > 4. 測試使用者應該獨立一個檔案對應一個，不同的測試用例之間不要互相依賴。
> > 
> 原始資料出處 : https://www.itread01.com/hkpqhkxx.html

### Go 單元測試範例 - 函式輸入與期望結果對比:
> ```go=
> //Basic_Unit_Testing1\Basic_Unit_Testing_Example1.go
> package Basic_Unit_Testing_Example1
> func fc_AddInt(vi_inputA, vi_inputB int) int {
> 	return vi_inputA + vi_inputB
> }
> ```
> 
> ```go=
> //Basic_Unit_Testing1\Basic_Unit_Testing_Example1_test.go
> package Basic_Unit_Testing_Example1
> 
> import (
> 	"fmt"
> 	"testing"
> )
> 
> func Test_fc_AddInt(testT *testing.T) {
> 
> 	var vs_theTestPanic string
> 	defer func() {
> 		if err_recover := recover(); err_recover != nil {
> 			testT.Fatalf("測試過程發生panic，本測項中止 -「%v」(%v)", vs_theTestPanic, err_recover)
> 		}
> 	}()
> 
> 	var stsl_Testers = []struct {
> 		add1 int
> 		add2 int
> 		want int
> 	}{
> 		{1, 1, 2},
> 		{2, 0, 2},
> 		{0, 2, 2},
> 		{9223372036854775807, -1, 9223372036854775806},
> 		{9223372036854775806, 1, 9223372036854775807},
> 		{9223372036854775807, 9223372036854775807, 0}, //overflows
> 		{-1, -1, -2},
> 	}
> 
> 	for vi_TestIndex, st_TestObject := range stsl_Testers {
> 		vs_theTestPanic = fmt.Sprintf("stsl_Testers[%v] %v", vi_TestIndex, st_TestObject)
> 		theTestResult := fc_AddInt(st_TestObject.add1, st_TestObject.add2)
> 		if theTestResult == st_TestObject.want {
> 			testT.Logf("項目測試正確 %v+%v=%v(%v)", st_TestObject.add1, st_TestObject.add2, st_TestObject.want, theTestResult)
> 		} else {
> 			testT.Errorf("項目測試[錯誤] %v+%v=%v(錯誤的結果:%v)", st_TestObject.add1, st_TestObject.add2, st_TestObject.want, theTestResult)
> 		}
> 	}
> }
> ```
> ```sass=
> d:\單元測試\Basic_Unit_Testing1>go test -v
> === RUN   Test_fc_AddInt
> --- FAIL: Test_fc_AddInt (0.00s)
>     Basic_Unit_Testing_Example1_test.go:35: 項目測試正確 1+1=2(2)
>     Basic_Unit_Testing_Example1_test.go:35: 項目測試正確 2+0=2(2)
>     Basic_Unit_Testing_Example1_test.go:35: 項目測試正確 0+2=2(2)
>     Basic_Unit_Testing_Example1_test.go:35: 項目測試正確 9223372036854775807+-1=9223372036854775806(9223372036854775806)
>     Basic_Unit_Testing_Example1_test.go:35: 項目測試正確 9223372036854775806+1=9223372036854775807(9223372036854775807)
>     Basic_Unit_Testing_Example1_test.go:37: 項目測試[錯誤] 9223372036854775807+9223372036854775807=0(錯誤的結果:-2)
>     Basic_Unit_Testing_Example1_test.go:35: 項目測試正確 -1+-1=-2(-2)
> FAIL
> exit status 1
> FAIL    Lesson4/單元測試/Basic_Unit_Testing1    0.026s
> ```

### Go 單元測試範例 - 函式輸入與錯誤回報:
> ```go=
> //Basic_Unit_Testing2\Basic_Unit_Testing_Example2.go
> package Basic_Unit_Testing_Example2
> import (
> 	"errors"
> )
> 
> func fc_DivInt(vi_inputA, vi_inputB int) int {
> 	return vi_inputA / vi_inputB
> }
> 
> func fc_DivIntMod(vi_inputA, vi_inputB int) (int, error) {
> 	if vi_inputB == 0 {
> 		return 0, errors.New("除數不得為0")
> 	}
> 	return vi_inputA / vi_inputB, nil
> }
> 
> ```
> 
> ```go=
> //Basic_Unit_Testing2\Basic_Unit_Testing_Example2_test.go
> package Basic_Unit_Testing_Example2
> 
> import (
> 	"errors"
> 	"fmt"
> 	"testing"
> )
> 
> func Test_fc_DivIntMod(testT *testing.T) {
> 
> 	var vs_theTestPanic string
> 	defer func() {
> 		if err_recover := recover(); err_recover != nil {
> 			testT.Fatalf("測試過程發生panic，本測項中止 -「%v」(%v)", vs_theTestPanic, err_recover)
> 		}
> 	}()
> 
> 	type ty_TestIndex struct {
> 		dividend int
> 		divisor  int
> 		want1    int
> 		want2    error
> 	}
> 
> 	var stsl_Testers = []ty_TestIndex{
> 		{1, 1, 1, nil},
> 		{10, 2, 5, nil},
> 		{0, 2, 0, nil},
> 		{9223372036854775807, 1, 9223372036854775807, nil},
> 		{9223372036854775806, 3, 3074457345618258602, nil},
> 		{9223372036854775807, 4611686018427387903, 2, nil},
> 		{9223372036854775807, 0, 0, errors.New("除數不得為0")}, //除零預期錯誤
> 		{-1, 1, -1, nil},
> 	}
> 
> 	for vi_TestIndex, st_TestObject := range stsl_Testers {
> 		vs_theTestPanic = fmt.Sprintf("stsl_Testers[%v] %v", vi_TestIndex, st_TestObject)
> 		theTestResult1, theTestResult2 := fc_DivIntMod(st_TestObject.dividend, st_TestObject.divisor)
> 
> 		if theTestResult2 == nil {
> 			theTestResult2 = errors.New("nil")
> 		}
> 		if st_TestObject.want2 == nil {
> 			st_TestObject.want2 = errors.New("nil")
> 		}
> 
> 		if theTestResult1 == st_TestObject.want1 && theTestResult2.Error() == st_TestObject.want2.Error() {
> 			testT.Logf("項目測試正確 %v/%v=%v,%v(%v,%v)", st_TestObject.dividend, st_TestObject.divisor, st_TestObject.want1, st_TestObject.want2, theTestResult1, theTestResult2)
> 		} else {
> 			testT.Errorf("項目測試[錯誤] %v/%v=%v,%v(錯誤的結果:%v,%v)", st_TestObject.dividend, st_TestObject.divisor, st_TestObject.want1, st_TestObject.want2, theTestResult1, theTestResult2)
> 		}
> 	}
> 
> }
> ```
> 
> ```sass=
> d:\單元測試\Basic_Unit_Testing2>go test -v
> === RUN   Test_fc_DivIntMod
> --- PASS: Test_fc_DivIntMod (0.00s)
>     Basic_Unit_Testing_Example2_test.go:48: 項目測試正確 1/1=1,nil(1,nil)
>     Basic_Unit_Testing_Example2_test.go:48: 項目測試正確 10/2=5,nil(5,nil)
>     Basic_Unit_Testing_Example2_test.go:48: 項目測試正確 0/2=0,nil(0,nil)
>     Basic_Unit_Testing_Example2_test.go:48: 項目測試正確 9223372036854775807/1=9223372036854775807,nil(9223372036854775807,nil)
>     Basic_Unit_Testing_Example2_test.go:48: 項目測試正確 9223372036854775806/3=3074457345618258602,nil(3074457345618258602,nil)
>     Basic_Unit_Testing_Example2_test.go:48: 項目測試正確 9223372036854775807/4611686018427387903=2,nil(2,nil)
>     Basic_Unit_Testing_Example2_test.go:48: 項目測試正確 9223372036854775807/0=0,除數不得為0(0,除數不得為0)
>     Basic_Unit_Testing_Example2_test.go:48: 項目測試正確 -1/1=-1,nil(-1,nil)
> PASS
> ok      Lesson4/單元測試/Basic_Unit_Testing2    0.025s
> ```

### Go 單元測試範例 - 雙函式結果對比(隨機輸入):
> ```go=
> //Basic_Unit_Testing3\Basic_Unit_Testing_Example3.go
> package Basic_Unit_Testing_Example3
> 
> func fc_SumA(via_Input ...int) int {
> 	var vi_sum int
> 	for i := 0; i < len(via_Input); i++ {
> 		vi_sum += via_Input[i]
> 	}
> 	return vi_sum
> }
> 
> func fc_SumB(vi_sum int, via_Input ...int) int {
> 	for i := 0; i < len(via_Input); i++ {
> 		vi_sum += via_Input[i]
> 	}
> 	return vi_sum
> }
> ```
> 
> ```go=
> //Basic_Unit_Testing3\Basic_Unit_Testing_Example_test3.go
> package Basic_Unit_Testing_Example3
> 
> import (
> 	"math/rand"
> 	"testing"
> 	"time"
> )
> 
> 
> func Test_fc_SumAnB(testT *testing.T) {
> 
> 	var vs_theTestPanic string
> 	defer func() {
> 		if err_recover := recover(); err_recover != nil {
> 			testT.Fatalf("測試過程發生panic，本測項中止 -「%v」(%v)", vs_theTestPanic, err_recover)
> 		}
> 	}()
> 
> 	theRandSeed := time.Now().UTC().UnixNano()
> 	rand.Seed(theRandSeed)
> 	var vi_RandInt int
> 	var vi_Output_fc_SumA int
> 	var vi_Output_fc_SumB int
> 
> 	for index := 0; index < 10; index++ {
> 		vi_RandInt = rand.Int()
> 		vi_Output_fc_SumA = fc_SumA(vi_RandInt)
> 		vi_Output_fc_SumB = fc_SumB(vi_RandInt)
> 		if fc_SumA(vi_RandInt) == fc_SumB(vi_RandInt) {
> 			testT.Logf("項目測試正確 %v=%v (亂數種子:%d,亂數int:%v)", vi_Output_fc_SumA, vi_Output_fc_SumB, theRandSeed, vi_RandInt)
> 		} else {
> 			testT.Errorf("項目測試[錯誤] %v=%v (亂數種子:%d,亂數int:%v)", vi_Output_fc_SumA, vi_Output_fc_SumB, theRandSeed, vi_RandInt)
> 		}
> 	}
> }
> 
> ```
> ```sass=
> d:\單元測試\Basic_Unit_Testing3>go test -v
> === RUN   Test_fc_SumAnB
> --- PASS: Test_fc_SumAnB (0.00s)
>     Basic_Unit_Testing_Example3_test.go:30: 項目測試正確 128637770004810965=128637770004810965 (亂數種子:1570086382169605200,亂數int:128637770004810965)
>     Basic_Unit_Testing_Example3_test.go:30: 項目測試正確 2710904496263871649=2710904496263871649 (亂數種子:1570086382169605200,亂數int:2710904496263871649)
>     Basic_Unit_Testing_Example3_test.go:30: 項目測試正確 7459572758933604767=7459572758933604767 (亂數種子:1570086382169605200,亂數int:7459572758933604767)
>     Basic_Unit_Testing_Example3_test.go:30: 項目測試正確 7058483080362729371=7058483080362729371 (亂數種子:1570086382169605200,亂數int:7058483080362729371)
>     Basic_Unit_Testing_Example3_test.go:30: 項目測試正確 7049057841437937710=7049057841437937710 (亂數種子:1570086382169605200,亂數int:7049057841437937710)
>     Basic_Unit_Testing_Example3_test.go:30: 項目測試正確 8952472848806917481=8952472848806917481 (亂數種子:1570086382169605200,亂數int:8952472848806917481)
>     Basic_Unit_Testing_Example3_test.go:30: 項目測試正確 7580769296778865075=7580769296778865075 (亂數種子:1570086382169605200,亂數int:7580769296778865075)
>     Basic_Unit_Testing_Example3_test.go:30: 項目測試正確 5973232751947046394=5973232751947046394 (亂數種子:1570086382169605200,亂數int:5973232751947046394)
>     Basic_Unit_Testing_Example3_test.go:30: 項目測試正確 2797291425107336826=2797291425107336826 (亂數種子:1570086382169605200,亂數int:2797291425107336826)
>     Basic_Unit_Testing_Example3_test.go:30: 項目測試正確 1338551253019334488=1338551253019334488 (亂數種子:1570086382169605200,亂數int:1338551253019334488)
> PASS
> ok      Lesson4/單元測試/Basic_Unit_Testing3    0.028s
> ```


### Go 效能測試範例 - (go test -bench=):
> 
> ```go=
> //d:\效能測試\Basic_Benchmark.go
> package Basic_Benchmark
> import "fmt"
> func fc_SprintInt(vi_input int) string {
> 	return fmt.Sprintf("%d", vi_input)
> }
> 
> ```
> 
> ```go=
> //d:\效能測試\Basic_Benchmark_test.go
> package Basic_Benchmark
> import "testing"
> func Benchmark_fc_SprintInt(benchB *testing.B) {
> 	benchB.ResetTimer()
> 	for i := 0; i < benchB.N; i++ {
> 		fc_SprintInt(99999)
> 	}
> }
> 
> ```
> go test -bench=. -cpu 1,2,3,4 -cpuprofile cpu.out -memprofile mem.out -blockprofile block.out
>
> ```sass=
> d:\效能測試>go test -bench=. -cpu 1,2,3,4 -cpuprofile cpu.out -memprofile mem.out -blockprofile block.out
> go test: missing argument for flag blockprofile
> run "go help test" or "go help testflag" for more information
> 
> d:\效能測試>go test -bench=. -cpu 1,2,3,4 -cpuprofile cpu.out -memprofile mem.out -blockprofile block.out
> goos: windows
> goarch: amd64
> pkg: Lesson4/效能測試
> Benchmark_fc_SprintInt          10000000               194 ns/op
> Benchmark_fc_SprintInt-2        10000000               163 ns/op
> Benchmark_fc_SprintInt-3        10000000               159 ns/op
> Benchmark_fc_SprintInt-4        10000000               139 ns/op
> PASS
> ok      Lesson4/效能測試        7.583s
> 
> d:\效能測試>go tool pprof -text -nodecount=10 cpu.out
> Type: cpu
> Time: Sep 3, 2019 at 5:35pm (CST)
> Duration: 7.45s, Total samples = 7300ms (97.99%)
> Showing nodes accounting for 4490ms, 61.51% of 7300ms total
> Dropped 46 nodes (cum <= 36.50ms)
> Showing top 10 nodes out of 52
>       flat  flat%   sum%        cum   cum%
>      830ms 11.37% 11.37%     1650ms 22.60%  runtime.mallocgc
>      800ms 10.96% 22.33%     1470ms 20.14%  fmt.(*fmt).fmtInteger
>      580ms  7.95% 30.27%     2600ms 35.62%  fmt.(*pp).doPrintf
>      380ms  5.21% 35.48%     2020ms 27.67%  fmt.(*pp).printArg
>      350ms  4.79% 40.27%      640ms  8.77%  sync.(*Pool).Get
>      350ms  4.79% 45.07%      630ms  8.63%  sync.(*Pool).Put
>      330ms  4.52% 49.59%     1430ms 19.59%  runtime.slicebytetostring
>      290ms  3.97% 53.56%      670ms  9.18%  fmt.(*fmt).pad
>      290ms  3.97% 57.53%     6140ms 84.11%  fmt.Sprintf
>      290ms  3.97% 61.51%      290ms  3.97%  runtime.memmove
> 
> d:\效能測試>go tool pprof -text -nodecount=10 mem.out
> Type: alloc_space
> Time: Sep 3, 2019 at 5:35pm (CST)
> Showing nodes accounting for 637.51MB, 99.50% of 640.68MB total
> Dropped 17 nodes (cum <= 3.20MB)
>       flat  flat%   sum%        cum   cum%
>   371.51MB 57.99% 57.99%   372.01MB 58.06%  fmt.Sprintf
>      266MB 41.52% 99.50%   638.01MB 99.58%  Lesson4/%e6%95%88%e8%83%bd%e6%b8%ac%e8%a9%a6.fc_SprintInt
>          0     0% 99.50%   638.01MB 99.58%  Lesson4/%e6%95%88%e8%83%bd%e6%b8%ac%e8%a9%a6.Benchmark_fc_SprintInt
>          0     0% 99.50%   638.01MB 99.58%  testing.(*B).launch
>          0     0% 99.50%   638.01MB 99.58%  testing.(*B).runN
> 
> d:\效能測試>go tool pprof -text -nodecount=10 block.out
> Type: delay
> Time: Sep 3, 2019 at 5:35pm (CST)
> Showing nodes accounting for 7466.18ms, 100% of 7466.19ms total
> Dropped 5 nodes (cum <= 37.33ms)
> Showing top 10 nodes out of 17
>       flat  flat%   sum%        cum   cum%
>  7466.18ms   100%   100%  7466.18ms   100%  runtime.chanrecv1
>          0     0%   100%  7466.19ms   100%  main.main
>          0     0%   100%  7466.19ms   100%  runtime.main
>          0     0%   100%   153.33ms  2.05%  runtime/pprof.StopCPUProfile
>          0     0%   100%   153.33ms  2.05%  sync.(*Once).Do
>          0     0%   100%  7312.85ms 97.95%  testing.(*B).Run
>          0     0%   100%  7311.72ms 97.93%  testing.(*B).doBench
>          0     0%   100%  7312.62ms 97.94%  testing.(*B).run
>          0     0%   100%  7312.85ms 97.95%  testing.(*B).runN
>          0     0%   100%  7466.19ms   100%  testing.(*M).Run
> 
> ```
### Go 涵蓋率測試範例 - (go tool cover):
> ```go=
> // 涵蓋率測試/Cover_Testing_Example.go
> package Cover_Testing_Example
> func fc_AddInt(vi_inputA, vi_inputB int) int {
> 	return vi_inputA + vi_inputB
> }
> 
> func fc_SubInt(vi_inputA, vi_inputB int) int {
> 	return vi_inputA - vi_inputB
> }
> 
> func fc_SumA(via_Input ...int) int {
> 	var vi_sum int
> 	for i := 0; i < len(via_Input); i++ {
> 		vi_sum += via_Input[i]
> 	}
> 	return vi_sum
> }
> 
> func fc_SumB(vi_sum int, via_Input ...int) int {
> 	for i := 0; i < len(via_Input); i++ {
> 		vi_sum += via_Input[i]
> 	}
> 	return vi_sum
> }
> ```
> 
> ```go=
> // 涵蓋率測試/Cover_Testing_Example_test.go
> package Cover_Testing_Example
> import (
> 	"fmt"
> 	"math/rand"
> 	"testing"
> 	"time"
> )
> 
> func Test_fc_AddInt(testT *testing.T) {
> 
> 	var vs_theTestPanic string
> 	defer func() {
> 		if err_recover := recover(); err_recover != nil {
> 			testT.Fatalf("測試過程發生panic，本測項中止 -「%v」(%v)", vs_theTestPanic, err_recover)
> 		}
> 	}()
> 
> 	var stsl_Testers = []struct {
> 		add1 int
> 		add2 int
> 		want int
> 	}{
> 		{1, 1, 2},
> 		{2, 0, 2},
> 		{0, 2, 2},
> 		{9223372036854775807, -1, 9223372036854775806},
> 		{9223372036854775806, 1, 9223372036854775807},
> 		{9223372036854775807, 9223372036854775807, 0}, //overflows
> 		{-1, -1, -2},
> 	}
> 
> 	for vi_TestIndex, st_TestObject := range stsl_Testers {
> 		vs_theTestPanic = fmt.Sprintf("stsl_Testers[%v] %v", vi_TestIndex, st_TestObject)
> 		theTestResult := fc_AddInt(st_TestObject.add1, st_TestObject.add2)
> 		if theTestResult == st_TestObject.want {
> 			testT.Logf("項目測試正確 %v+%v=%v(%v)", st_TestObject.add1, st_TestObject.add2, st_TestObject.want, theTestResult)
> 		} else {
> 			testT.Errorf("項目測試[錯誤] %v+%v=%v(錯誤的結果:%v)", st_TestObject.add1, st_TestObject.add2, st_TestObject.want, theTestResult)
> 		}
> 	}
> }
> 
> func Test_fc_SumAnB(testT *testing.T) {
> 
> 	var vs_theTestPanic string
> 	defer func() {
> 		if err_recover := recover(); err_recover != nil {
> 			testT.Fatalf("測試過程發生panic，本測項中止 -「%v」(%v)", vs_theTestPanic, err_recover)
> 		}
> 	}()
> 
> 	theRandSeed := time.Now().UTC().UnixNano()
> 	rand.Seed(theRandSeed)
> 	var vi_RandInt int
> 	var vi_Output_fc_SumA int
> 	var vi_Output_fc_SumB int
> 
> 	for index := 0; index < 10; index++ {
> 		vi_RandInt = rand.Int()
> 		vi_Output_fc_SumA = fc_SumA(vi_RandInt)
> 		vi_Output_fc_SumB = fc_SumB(vi_RandInt)
> 		if fc_SumA(vi_RandInt) == fc_SumB(vi_RandInt) {
> 			testT.Logf("項目測試正確 %v=%v (亂數種子:%d,亂數int:%v)", vi_Output_fc_SumA, vi_Output_fc_SumB, theRandSeed, vi_RandInt)
> 		} else {
> 			testT.Errorf("項目測試[錯誤] %v=%v (亂數種子:%d,亂數int:%v)", vi_Output_fc_SumA, vi_Output_fc_SumB, theRandSeed, vi_RandInt)
> 		}
> 	}
> }
> 
> ```
> 
> ```sass=
> PS D:\涵蓋率測試> go test -v -cover -coverprofile cover.out
> === RUN   Test_fc_AddInt
> --- FAIL: Test_fc_AddInt (0.00s)
>     Cover_Testing_Example_test.go:37: 項目測試正確 1+1=2(2)
>     Cover_Testing_Example_test.go:37: 項目測試正確 2+0=2(2)
>     Cover_Testing_Example_test.go:37: 項目測試正確 0+2=2(2)
>     Cover_Testing_Example_test.go:37: 項目測試正確 9223372036854775807+-1=9223372036854775806(9223372036854775806)
>     Cover_Testing_Example_test.go:37: 項目測試正確 9223372036854775806+1=9223372036854775807(9223372036854775807)
>     Cover_Testing_Example_test.go:39: 項目測試[錯誤] 9223372036854775807+9223372036854775807=0(錯誤的結果:-2)
>     Cover_Testing_Example_test.go:37: 項目測試正確 -1+-1=-2(-2)
> === RUN   Test_fc_SumAnB
> --- PASS: Test_fc_SumAnB (0.00s)
>     Cover_Testing_Example_test.go:64: 項目測試正確 1054791156209780183=1054791156209780183 (亂數種子:1570164062516555300,亂數int:1054791156209780183)
>     Cover_Testing_Example_test.go:64: 項目測試正確 1572036677946546427=1572036677946546427 (亂數種子:1570164062516555300,亂數int:1572036677946546427)
>     Cover_Testing_Example_test.go:64: 項目測試正確 4043804078525964286=4043804078525964286 (亂數種子:1570164062516555300,亂數int:4043804078525964286)
>     Cover_Testing_Example_test.go:64: 項目測試正確 4490900911252265608=4490900911252265608 (亂數種子:1570164062516555300,亂數int:4490900911252265608)
>     Cover_Testing_Example_test.go:64: 項目測試正確 9189757511242968573=9189757511242968573 (亂數種子:1570164062516555300,亂數int:9189757511242968573)
>     Cover_Testing_Example_test.go:64: 項目測試正確 8466299651324370872=8466299651324370872 (亂數種子:1570164062516555300,亂數int:8466299651324370872)
>     Cover_Testing_Example_test.go:64: 項目測試正確 600841189896519269=600841189896519269 (亂數種子:1570164062516555300,亂數int:600841189896519269)
>     Cover_Testing_Example_test.go:64: 項目測試正確 8783876916636026197=8783876916636026197 (亂數種子:1570164062516555300,亂數int:8783876916636026197)
>     Cover_Testing_Example_test.go:64: 項目測試正確 4035231185535482081=4035231185535482081 (亂數種子:1570164062516555300,亂數int:4035231185535482081)
>     Cover_Testing_Example_test.go:64: 項目測試正確 4089254982128445097=4089254982128445097 (亂數種子:1570164062516555300,亂數int:4089254982128445097)
> FAIL
> coverage: 77.8% of statements
> exit status 1
> FAIL    Lesson4/涵蓋率測試      0.029s
> ```
> **go tool cover** 工具指令獲得到測試涵蓋率 **77.8%** ，可藉由下方指令分析測試過程中涵蓋的程式碼 **Cover_Testing_Example.go** :
> 
> ```sass=
> PS D:\涵蓋率測試> go tool cover -html cover.out
> ```
> ![image alt](https://lh3.googleusercontent.com/xWF5qZCGn-4-CEi_I2WoXnr4pWKHtUa8hIImcQ2ccXH-2xdGnGJviL3N_7srGRAFKpyZ2uTN3dnJeDdgQMgBx3scTIC4hnw-_HdhRSX3q0AeJKvB3BCbBiQfhNSzsbL_1yl6ML_Hu-yyvC46HlKf1EiHw4LHxQlIU7EGchH2f8bajHo0oiHMMmQYcdjt1zxBb5lP2_gneppxjpGqsgtKoZzHDpaS91r-A8-4c6zMipGYWeUxOy77ssO9QkVX_v-8zUCsm_Y0_WuvKex3_G66Uwr7K1WGydBW_PY0BU0jFmzmE3lMpeOZxs29NeJgKbk98BMEQ1OW323Wpl2SNnpSiISOSYhtgeeksUaD8xD2BWIHCW3WzfekzSO2fran24nbLiJZEmhDNUA1pDX4iA48G0L-iCLXuHJVykt-SoVqhHyG6L3WPWxyk5y4Tt7uC-SXohsrWfl9bhaZNkva2zJc8BgNZLjMoz15yfvn1r12RbCWkClr_P1HEmcRne-FO2TQUuthvQIHf_AjgoFOzA3c5NSYkUjDArZJHNeH-ozg6Fj8KCZEuKaxYgcxlc-k1GMc34VVr5OO8a1OaErCrLJ4FMnhygjpA3m3ZlJWS25yO7VC_6BK0kGRutju5DiPwFO0KPjLGUwd4VPkoTdc7oRyEjZJSoB275XlnpCsue7-Vp-lWM1hGxLCcAHL=w676-h583-no "title")
> * 紅色部分表示測試未涵蓋到的程式碼


---

### Go 氣泡排序法(Bubble Sort):
> 氣泡排序演算法的運作如下：
> 1.比較相鄰的元素。如果第一個比第二個大，就交換他們兩個。
> 2.對每一對相鄰元素作同樣的工作，從開始第一對到結尾的最後一對。
>　這步做完後，最後的元素會是最大的數。
> 3.針對所有的元素重複以上的步驟，除了最後一個。
> 4.持續每次對越來越少的元素重複上面的步驟，直到沒有任何一對數字需要比較。
><iframe width=100% height="315" src="https://www.youtube.com/embed/O2w-gJjU-PU?start=266" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
>
> ```go
> package main
> import "fmt"
> func main() {
> 
> 	var vSlice = []int{51, 99, 36, 66, 62}
> 	fmt.Println("排序前:", vSlice)
> 	fmt.Println("最後結果:", fcBubbleSort_Slice(vSlice))
> 
> }
> 
> func fcBubbleSort_Slice(inputSlice []int) []int {
> 	for index1 := 1; index1 < len(inputSlice); index1++ {
> 		// 第一層迴圈負責控制排序輪迴數
> 		// 每輪都從第二個元素開始，將最大的值交換到最後一位
> 		for index2 := 0; index2 < len(inputSlice)-index1; index2++ {
> 			// 第二層迴圈負責比較兩元素大小判斷是否交換
> 			if inputSlice[index2] > inputSlice[index2+1] {
> 				inputSlice[index2], inputSlice[index2+1] = inputSlice[index2+1], inputSlice[index2]
> 			}
> 		}
> 		fmt.Printf("第%v次排序結果: %v\n", index1, inputSlice)
> 	}
> 	return inputSlice
> }
> ```


### Go 檔案管理包(os.File):

> #### os.file包使用說明:
> | 函式名稱 | 說明 | 輸入 | 輸出類型:::: |
> | - | - | -   | - | 
> | os.Open(路徑) |打開路徑中的檔案，並將輸出該文件的指標|(string)|(*file error)|
> | (*file).Close() |將關閉file指標所指向檔案，移除移除該file指標|(string)|(error)|
>
> os.OpenFile(name string, flag int, perm FileMode) (file *File, err error)
> ==`FileMode:`==
>| 函式名稱 | 說明 | 
> | - | - | -   | - | 
> | O_RDONLY | 只讀模式打開文件 |
> | O_WRONLY | 只寫模式打開文件 |
> | O_RDWR | 讀寫模式打開文件 |
> | O_APPEND | 寫操作時將數據附加到文件尾部 |
> | O_CREAT | 如果不存在將創建一個新文件 |
> | O_EXCL | 和O_CREATE配合使用，文件必須不存在 |
> | O_SYNC | 打開文件用於同步I/O |
> | O_TRUNC | 如果可能，打開時清空文件 |
> 



### Go 參數命令列(os&flag)應用:
> ```go=
> package main
> 
> import (
> 	"flag"
> 	"fmt"
> 	"os"
> )
> 
> func main() {
> 
> 	//os.Args為string切片類型
> 	fmt.Printf("一共接收到: %v 個參數 (%T)\n", len(os.Args), os.Args)
> 
> 	for index, value := range os.Args {
> 		fmt.Printf("os.Args[%v]=%v\n", index, value)
> 	} //os.Args命令列參數具備次序性
> 
> 	fmt.Println()
> 	fmt.Println()
> 	////////////////////////////////
> 
> 	var user string
> 	var pwd string
> 	var port int
> 
> 	flag.StringVar(&user, "u", "預設用戶名", "用戶名")
> 	flag.StringVar(&pwd, "pwd", "", "密碼")
> 	flag.IntVar(&port, "port", 0, "Port")
> 
> 	flag.Parse() //flag解析命令列參數
> 
> 	fmt.Printf("User=%v\nPwd=%v\nPort=%v\n", user, pwd, port)
> 
> 	// cmd.exe -u 123 -pwd "密碼測試" -port 00
> 	// 一共接收到: 7 個參數 ([]string)
> 	// os.Args[0]=cmd.exe
> 	// os.Args[1]=-u
> 	// os.Args[2]=123
> 	// os.Args[3]=-pwd
> 	// os.Args[4]=密碼測試
> 	// os.Args[5]=-port
> 	// os.Args[6]=00
> 
> 	// User=123
> 	// Pwd=密碼測試
> 	// Port=0
> 
> }
> ```
> 

### Go 常用資料格式(json)應用:
==`json.Marshal`==
```go=
package main

import (
	"encoding/json"
	"fmt"
)

func main() {

	//////////////////////////////////////////////////////////////////
	// 將結構體輸出成json格式
	type stMonster struct {
		Name   string //json包輸入變數必須大寫
		Age    int
		Weight float64
	}

	var oMonster = stMonster{
		Name: "名稱",
		Age:  99,
	}

	vData, err := json.Marshal(&oMonster)
	if err != nil {
		fmt.Printf("json.Marshal錯誤 : %v\n", err)
	} else {
		fmt.Printf("json.Marshal解析結果 : %v\n", string(vData))
	}
	// json.Marshal解析結果 : {"Name":"名稱","Age":99,"Weight":0}
	/////////////////////////////////////////////////////////////////

	//////////////////////////////////////////////////////////////////
	// 將結構體輸出成json格式
	type stMonsterJ struct {
		Name   string  `json:"json名稱"`
		Age    int     `json:"json年齡"`
		Weight float64 `json:"json重量"`
	}

	var oMonsterJ = stMonsterJ{
		Name:   "JJJJ",
		Age:    00,
		Weight: 0.0,
	}

	vData, err = json.Marshal(&oMonsterJ)
	if err != nil {
		fmt.Printf("json.Marshal錯誤 : %v\n", err)
	} else {
		fmt.Printf("json.Marshal解析結果 : %v\n", string(vData))
	}
	//json.Marshal解析結果 : {"json名稱":"JJJJ","json年齡":0,"json重量":0}
	/////////////////////////////////////////////////////////////////

	/////////////////////////////////////////////////////////////////
	// 將map輸出成json格式
	var mData map[string]interface{}
	mData = make(map[string]interface{})
	mData["Name"] = "名稱測試"
	mData["Age"] = 18
	mData["Weight"] = 99.0

	vData, err = json.Marshal(&mData)
	if err != nil {
		fmt.Printf("json.Marshal錯誤 : %v\n", err)
	} else {
		fmt.Printf("json.Marshal解析結果 : %v\n", string(vData))
	}
	//json.Marshal解析結果 : {"Age":18,"Name":"名稱測試","Weight":99}
	/////////////////////////////////////////////////////////////////

	/////////////////////////////////////////////////////////////////
	// 將切片加入空接口並寫入map元素輸出成json格式
	var sSlice []map[string]interface{}

	var mData1 map[string]interface{}
	mData1 = make(map[string]interface{})
	mData1["Name"] = "名稱測試"
	mData1["Age"] = 18
	mData1["Weight"] = 99.0

	var mData2 map[string]interface{}
	mData2 = make(map[string]interface{})
	mData2["Name"] = "名稱測試"
	mData2["Age"] = 18
	mData2["Weight"] = 99.0

	sSlice = append(sSlice, mData1, mData2)

	vData, err = json.Marshal(sSlice)
	if err != nil {
		fmt.Printf("json.Marshal錯誤 : %v\n", err)
	} else {
		fmt.Printf("json.Marshal解析結果 : %v\n", string(vData))
	}
	//json.Marshal解析結果 : [{"Age":18,"Name":"名稱測試","Weight":99},{"Age":18,"Name":"名稱測試","Weight":99}]
	/////////////////////////////////////////////////////////////////

}

```

==`json.Unmarshal`==
```go=
package main

import (
	"encoding/json"
	"fmt"
)

func main() {
	var err error

	sSlice := []byte(`{"Name":"柏崎星奈","Age":16,"Married":false}`)
	// interface 可以接收任何類型的值
	var mMap map[string]interface{}
	err = json.Unmarshal(sSlice, &mMap) //Unmarshal只能接收
	if err != nil {
		panic(err)
	}
	fmt.Println("Name: ", mMap["Name"])
	fmt.Println("Age: ", mMap["Age"])
	fmt.Printf("Married: %v\n", mMap["Married"].(bool)) // interface 也可以直接轉成你要的型別
	fmt.Println()

	// Name:  柏崎星奈
	// Age:  16
	// Married: false

	type Identification struct {
		Phone string `json:"JPhone"`
		Email string `json:"JEmail"`
	}

	type User struct {
		ID             int
		Name           string
		Skills         []string
		Relationship   map[string]string
		Identification Identification
	}

	var sJsonBlob = []byte(`{"錯誤":"雜訊","Name":"人員名稱","Skills":["玩","運動"],"Relationship":{"Dad":"Hulk","Mon":"Natasha"},"Identification":{"JPhone":"cc@cc.com","JEmail":false}}`)
	var stUser User
	err = json.Unmarshal(sJsonBlob, &stUser)
	if err != nil {
		fmt.Println("error:", err)
	}
	fmt.Printf("%+v", stUser)
	fmt.Println()
	// error: json: cannot unmarshal bool into Go struct field Identification.JEmail of type string  //該錯誤為 "JEmail":false 所產生
	// {ID:0 Name:人員名稱 Skills:[玩 運動] Relationship:map[Dad:Hulk Mon:Natasha] Identification:{Phone:cc@cc.com Email:}}
	// 多餘的切片元素將會被json.Unmarshal棄置
}

```

### Go 注入(inject)(github)應用:
==`go get github.com/codegangsta/inject`==
```go=
package main
import (
	"fmt"

	"github.com/codegangsta/inject"
)

/*
	github.com/codegangsta/inject 利用反射(reflect)包所設計，
	可將自動將變數注入到func和struct中，實現變數自動排列輸入

*/

type TY_S1 interface{}
type TY_S2 interface{}

type Ty_Staff struct {
	Name    string `inject`
	Company TY_S1  `inject`
	Level   TY_S2  `inject`
	Age     int    `inject`
}

func FC_PrintData(vs_name string, if_company TY_S1, if_level TY_S2, vi_age int) {
	fmt.Printf("name=%s, company=%s, level=%s, age=%d\n", vs_name, if_company, if_level, vi_age)
}

func main() {

	InjectNew := inject.New()
	InjectNew.Map("姓名")
	InjectNew.MapTo("公司名稱", (*TY_S1)(nil))
	InjectNew.MapTo("職稱", (*TY_S2)(nil))
	InjectNew.Map(23)
	InjectNew.Invoke(FC_PrintData) //name=姓名, company=公司名稱, level=職稱, age=99

	st_Staff := Ty_Staff{}
	InjectNew.Apply(&st_Staff)
	fmt.Printf("%v\n", st_Staff) //{XX 公司名稱 職稱 99}

	println()
	/////////////////////////////////////////////////////////////////////////////////////////////////////////

	InjectNewE := inject.New()
	InjectNewE.Map("姓名")
	InjectNewE.MapTo("公司名稱", (*TY_S1)(nil))
	InjectNewE.MapTo("職稱", (*TY_S2)(nil))
	InjectNewE.Map(23)

	InjectNewE.Map("覆寫姓名")
	InjectNewE.MapTo("覆寫公司名稱", (*TY_S1)(nil))
	InjectNewE.MapTo("覆寫職稱", (*TY_S2)(nil))
	InjectNewE.Map(99)
	InjectNewE.Map(11.11) //多餘資料

	InjectNewE.Invoke(FC_PrintData) //name=覆寫姓名, company=覆寫公司名稱, level=覆寫職稱, age=99

	st_StaffE := Ty_Staff{}
	InjectNewE.Apply(&st_StaffE)
	fmt.Printf("%v\n", st_StaffE) //{覆寫姓名 覆寫公司名稱 覆寫職稱 99}

}
```

### Go Protobuf (proto3)應用:


[參考資料](https://yami.io/protobuf/)
[變數型別(proto3)](https://developers.google.com/protocol-buffers/docs/proto3)

```bash
##Golang proto套件安裝
go get -u github.com/golang/protobuf/{proto,protoc-gen-go}
```

```bash
# Ubuntu安裝
curl -OL https://github.com/protocolbuffers/protobuf/releases/download/v3.10.1/protoc-3.10.1-linux-x86_64.zip
su
unzip protoc-3.10.1-linux-x86_64.zip -d protoc3

# 移動
mv protoc3/bin/* /usr/local/bin/
mv protoc3/include/* /usr/local/include/

# 修改權限
chown [user] /usr/local/bin/protoc
chown -R [user] /usr/local/include/google
```

```bash
## windows安裝protoc後必須另外將protoc.exe環境變數%Path%內
## protoc-gen-go.exe必須與protoc.exe在同一資料夾
copy protoc-gen-go.exe %Path%
```
Golang範例:

==`./person.proto`==:
``` go
syntax="proto3";

package main;

message Person {
      string name = 1;
      int32 age = 2;
}
```

```bash
## 將person.proto生成 person.pb.go
protoc --go_out=. person.proto
```

==`./person.pb.go`==:
```go=
// Code generated by protoc-gen-go. DO NOT EDIT.
// source: person.proto

package main

import (
	fmt "fmt"
	math "math"

	proto "github.com/golang/protobuf/proto"
)

// Reference imports to suppress errors if they are not otherwise used.
var _ = proto.Marshal
var _ = fmt.Errorf
var _ = math.Inf

// This is a compile-time assertion to ensure that this generated file
// is compatible with the proto package it is being compiled against.
// A compilation error at this line likely means your copy of the
// proto package needs to be updated.
const _ = proto.ProtoPackageIsVersion3 // please upgrade the proto package

type Person struct {
	Name                 string   `protobuf:"bytes,2,opt,name=name,proto3" json:"Name,omitempty"`
	Age                  int32    `protobuf:"varint,3,opt,name=age,proto3" json:"age,omitempty"`
	XXX_NoUnkeyedLiteral struct{} `json:"-"`
	XXX_unrecognized     []byte   `json:"-"`
	XXX_sizecache        int32    `json:"-"`
}

func (m *Person) Reset()         { *m = Person{} }
func (m *Person) String() string { return proto.CompactTextString(m) }
func (*Person) ProtoMessage()    {}
func (*Person) Descriptor() ([]byte, []int) {
	return fileDescriptor_4c9e10cf24b1156d, []int{0}
}

func (m *Person) XXX_Unmarshal(b []byte) error {
	return xxx_messageInfo_Person.Unmarshal(m, b)
}
func (m *Person) XXX_Marshal(b []byte, deterministic bool) ([]byte, error) {
	return xxx_messageInfo_Person.Marshal(b, m, deterministic)
}
func (m *Person) XXX_Merge(src proto.Message) {
	xxx_messageInfo_Person.Merge(m, src)
}
func (m *Person) XXX_Size() int {
	return xxx_messageInfo_Person.Size(m)
}
func (m *Person) XXX_DiscardUnknown() {
	xxx_messageInfo_Person.DiscardUnknown(m)
}

var xxx_messageInfo_Person proto.InternalMessageInfo

func (m *Person) GetName() string {
	if m != nil {
		return m.Name
	}
	return ""
}

func (m *Person) GetAge() int32 {
	if m != nil {
		return m.Age
	}
	return 0
}

func init() {
	proto.RegisterType((*Person)(nil), "main.Person")
}

func init() { proto.RegisterFile("person.proto", fileDescriptor_4c9e10cf24b1156d) }

var fileDescriptor_4c9e10cf24b1156d = []byte{
	// 88 bytes of a gzipped FileDescriptorProto
	0x1f, 0x8b, 0x08, 0x00, 0x00, 0x00, 0x00, 0x00, 0x02, 0xff, 0xe2, 0xe2, 0x29, 0x48, 0x2d, 0x2a,
	0xce, 0xcf, 0xd3, 0x2b, 0x28, 0xca, 0x2f, 0xc9, 0x17, 0x62, 0xc9, 0x4d, 0xcc, 0xcc, 0x53, 0xd2,
	0xe3, 0x62, 0x0b, 0x00, 0x8b, 0x0a, 0x09, 0x71, 0xb1, 0xf8, 0x25, 0xe6, 0xa6, 0x4a, 0x30, 0x29,
	0x30, 0x6a, 0x70, 0x06, 0x81, 0xd9, 0x42, 0x02, 0x5c, 0xcc, 0x89, 0xe9, 0xa9, 0x12, 0xcc, 0x0a,
	0x8c, 0x1a, 0xac, 0x41, 0x20, 0x66, 0x12, 0x1b, 0x58, 0xb3, 0x31, 0x20, 0x00, 0x00, 0xff, 0xff,
	0xf8, 0xbc, 0xb8, 0xfe, 0x4c, 0x00, 0x00, 0x00,
}


```

==`./main.go`==:
```go
package main

import (
	"fmt"

	"github.com/golang/protobuf/proto"
)

func main() {

	elliot := &Person{
		Name: "Elliot",
		Age:  24,
	}

	sl_ProtobufExample, err := proto.Marshal(elliot)
	if err != nil {
		fmt.Println("marshaling error: ", err)
	}
	fmt.Printf("%s\n", sl_ProtobufExample) //?Elliot

	st_UnProtoExample := &Person{}
	err = proto.Unmarshal(sl_ProtobufExample, st_UnProtoExample)
	if err != nil {
		fmt.Println("unmarshaling error: ", err)
	}

	fmt.Println(st_UnProtoExample) //name:"Elliot" age:24

}

```







### Go : if-else 執行結果效能驗證
```go=
package main

import (
	"log"
	"time"
)

func main() {

	check := 1

	time.Sleep(time.Second * 1)
	counter1 := StartTimer()
	var ss1 string
	for i := 0; i < 9999999999; i++ {
		if check == 0 {
			ss1 = "hhhhhhhhhhhhhhhhhhhhh"
		} else if check == 1 {
			ss1 = "hhhhhhhhhhhhhhhhhhhhh"
		} else {
			ss1 = "hhhhhhhhhhhhhhhhhhhhh"
		}

	}
	println(ss1)
	log.Printf("耗費:%.4f ms", SubTimer(counter1))
	// 	hhhhhhhhhhhhhhhhhhhhh
	// 2019/11/20 20:39:44 耗費:6962.3841 ms

	time.Sleep(time.Second * 1)
	counter2 := StartTimer()
	var ss2 string
	for i := 0; i < 9999999999; i++ {
		if check == 1 {
			ss2 = "hhhhhhhhhhhhhhhhhhhhh"
		} else if check == 0 {
			ss2 = "hhhhhhhhhhhhhhhhhhhhh"
		} else {
			ss2 = "hhhhhhhhhhhhhhhhhhhhh"
		}

	}
	println(ss2)
	log.Printf("耗費:%.4f ms", SubTimer(counter2))
	// 	hhhhhhhhhhhhhhhhhhhhh
	// 2019/11/20 20:39:45 耗費:6586.8364 ms

	time.Sleep(time.Second * 1)
	counter3 := StartTimer()
	var ss3 string
	for i := 0; i < 9999999999; i++ {
		if check == 0 {
			ss3 = "hhhhhhhhhhhhhhhhhhhhh"
		} else if check == 2 {
			ss3 = "hhhhhhhhhhhhhhhhhhhhh"
		} else {
			ss3 = "hhhhhhhhhhhhhhhhhhhhh"
		}

	}
	println(ss3)
	log.Printf("耗費:%.4f ms", SubTimer(counter3))
	// 	hhhhhhhhhhhhhhhhhhhhh
	// 2019/11/20 20:39:46 耗費:6586.8365 ms

	//三者測試結果差異極小，一般而言最常發生狀況應放置於第一個if或是最後才判斷的else
}

func StartTimer() time.Time {
	return time.Now()
}
func SubTimer(input time.Time) float64 {
	return time.Now().Sub(input).Seconds() * 1000
}

```

### Go : Map-Struct 測試效能驗證:
```go=
package main

import (
	"fmt"
	"log"
	"time"
)

type resp struct {
	n     int
	name  string
	data1 string
	data2 string
	data3 string
	data4 string
	data5 string
	data6 string
}

func NewResp(n int, name, data1, data2, data3, data4, data5, data6 string) *resp {
	return &resp{n, name, data1, data2, data3, data4, data5, data6}
}

func (r *resp) Update(n int, name, data1, data2, data3, data4, data5, data6 string) {
	r.n = n
	r.name = name
	r.data1 = data1
	r.data2 = data2
	r.data3 = data3
	r.data4 = data4
	r.data5 = data5
	r.data6 = data6
}

var mp = make(map[string]*resp)

func main() {

	counter1 := StartTimer()
	var resp1 *resp
	for i := 0; i < 9999999; i++ {
		resp1 = NewResp(i, "st", "1", "2", "3", "4", "5", "6")
	}
	fmt.Println(resp1)
	log.Printf("resp1 = NewResp() 耗費:%.4f ms", SubTimer(counter1))
	//2019/11/20 19:58:38 resp1 = NewResp() 耗費:931.1182 ms

	time.Sleep(time.Second * 1)
	counter2 := StartTimer()
	var resp2 resp
	for i := 0; i < 9999999; i++ {
		resp2.Update(i, "st", "1", "2", "3", "4", "5", "6")
	}
	fmt.Println(resp2)
	log.Printf("resp2.Update() 耗費:%.4f ms", SubTimer(counter2))
	//2019/11/20 19:58:38 resp2.Update() 耗費:72.0092 ms

	time.Sleep(time.Second * 1)
	counter3 := StartTimer()
	mp["key"] = &resp{}
	for i := 0; i < 9999999; i++ {
		mp["key"].Update(i, "st", "1", "2", "3", "4", "5", "6")
	}
	fmt.Println(mp["key"])
	delete(mp, "key")
	log.Printf("resp3.Update() 耗費:%.4f ms", SubTimer(counter3))
	//2019/11/20 19:58:38 resp3.Update() 耗費:166.0211 ms

}

func StartTimer() time.Time {
	return time.Now()
}
func SubTimer(input time.Time) float64 {
	return time.Now().Sub(input).Seconds() * 1000
}

```

### Go : Call Func by name (使用Map):
```go=
package main
import (
	"errors"
	"fmt"
	"reflect"
)

func fc_MapCallFunc(mp_FuncList map[string]interface{}, vs_FuncName string, if_InputArgs ...interface{}) (sl_Output []interface{}, err error) {

	defer func() {
		if err_recover := recover(); err_recover != nil {
			sl_Output = nil
			err = errors.New("fc_MapCallFunc > " + err_recover.(string))
		}
	}()

	ty_FuncValue := reflect.ValueOf(mp_FuncList[vs_FuncName])

	ty_FuncInputs := make([]reflect.Value, len(if_InputArgs))
	for index, value := range if_InputArgs {
		ty_FuncInputs[index] = reflect.ValueOf(value)

	}

	for _, value := range ty_FuncValue.Call(ty_FuncInputs) {
		sl_Output = append(sl_Output, value)
	}

	err = nil

	return

}

func main() {

	var mp_TheFunc = make(map[string]interface{})
	mp_TheFunc["Custom1"] = SayIt
	fc_MapCallFunc(mp_TheFunc, "Custom1", "ba la ba la")
	//fc_MapCallFunc(雜湊表名稱,函數的Key,輸入參數(變數)...)
	//ba la ba la

	println()

	mp_TheFunc["Custom2"] = CalAdder1
	vi_Result2, err := fc_MapCallFunc(mp_TheFunc, "Custom2", 1, 2, 3, 4)
	if err != nil {
		fmt.Printf("%v\n", err)
	} else {
		fmt.Printf("%v\n", vi_Result2[0])
	}
	// CalAdder1() 輸入參數(變數)限定3個，若輸入不正確的參數數量則返回錯誤!
	// fc_MapCallFunc > reflect: Call with too many input arguments
	println()

	mp_TheFunc["Custom3"] = CalAdder2
	vi_Result3, err := fc_MapCallFunc(mp_TheFunc, "Custom3", 1, 2, 3, 4)
	if err != nil {
		fmt.Printf("%v\n", err)
	} else {
		fmt.Printf("%v\n", vi_Result3[0])
		fmt.Printf("%v\n", vi_Result3[1])
	}
	// 第一個輸出 : 10
	// 第二個輸出 : nothing...

}

func SayIt(vs_input string) {
	fmt.Println(vs_input)
}

func CalAdder1(a, b, c int) int {
	return a + b + c
}

func CalAdder2(vi_input ...int) (sum int, nothing string) {
	for _, value := range vi_input {
		sum += value
	}
	nothing = "nothing..."
	return
}

```

### Go : Console輸入介面製作:
```go=
package main
import (
	"bufio"
	"errors"
	"fmt"
	"os"
	"strings"
)

func main() {

	var ty_input Console
	for {
		sl_Output, _ := ty_input.toSliceStr()
		fmt.Printf("%q\n", sl_Output)
	}

	//測試輸入 >  " 1 " 2 3 "4 " " 5" " 六六 " " 七 七 " "八 " " 九" "" " "
	//得到結果 > [" 1 " "2" "3" "4 " " 5" " 六六 " " 七 七 " "八 " " 九" "" " "]
	//引號內的空白將會寫入切片元素中

}

type Console string

func (input Console) toString() (string, error) {
	ty_Scanner := bufio.NewScanner(os.Stdin)
	//ty_Scanner := bufio.NewScanner(strings.NewReader("\" 1 \" 2 3 \"4 \" \" 5\" \" 六六 \" \" 七 七 \" \"八 \" \" 九\" \"\" \" \""))
	if ty_Scanner.Scan() {
		vs_Output := ty_Scanner.Text()
		if strings.Contains(vs_Output, "\r") || strings.Contains(vs_Output, "\n") || strings.Contains(vs_Output, "\t") {
			return "", errors.New("Can't contain ontains : \r \n \t")
		} else if strings.Count(vs_Output, "\"")%2 != 0 {
			return "", errors.New("Must be double-quote characters ( \" )")
		} else {
			return strings.TrimSpace(vs_Output), nil
		}
	} else {
		return "", nil
	}
}

func (input Console) toSliceStr() ([]string, error) {

	ty_Scanner := bufio.NewScanner(os.Stdin)
	//" 1 " 2 3 "4 " " 5" " 六六 " " 七 七 " "八 " " 九" "" " "
	//ty_Scanner := bufio.NewScanner(strings.NewReader("\" 1 \" 2 3 \"4 \" \" 5\" \" 六六 \" \" 七 七 \" \"八 \" \" 九\" \"\" \" \"")) //性能測試用 2019/11/25 14:34:50 耗費:1033.0591 ms
	//1 2 " 3 " "4 " " 5" " 六六 " " 七 七 " "八 " " 九" "" " "
	//ty_Scanner := bufio.NewScanner(strings.NewReader("1 2 \" 3 \" \"4 \" \" 5\" \" 六六 \" \" 七 七 \" \"八 \" \" 九\" \"\" \" \""))
	if ty_Scanner.Scan() {
		vs_Output := ty_Scanner.Text()

		if strings.Contains(vs_Output, "\r") || strings.Contains(vs_Output, "\n") || strings.Contains(vs_Output, "\t") {
			return nil, errors.New("Can't contain ontains : \r \n \t")
		} else if strings.Count(vs_Output, "\"")%2 != 0 {
			return nil, errors.New("Must be double-quote characters ( \" )")
		} else {

			vs_Output = strings.TrimSpace(vs_Output)
			var vi_QutaCount uint64
			for _, value := range []rune(vs_Output) {
				if string(value) == "\"" {
					vi_QutaCount++
					if vi_QutaCount%2 == 1 {
						vs_Output = strings.Replace(vs_Output, "\"", "\r", 1) //<

					} else {
						vs_Output = strings.Replace(vs_Output, "\"", "\n", 1) //>
					}
				}
			}

			vs_Output = strings.ReplaceAll(vs_Output, " \r>", "") //<>

			sl_Output := strings.Split(vs_Output, "\r") //<
			for _, value := range sl_Output {
				vi_ChrIndex := strings.Index(value, "\n") //>
				if vi_ChrIndex > 0 {
					vi_ChrCache := strings.ReplaceAll(value[:vi_ChrIndex+1], " ", "\t") //*
					vs_Output = strings.Replace(vs_Output, value[:vi_ChrIndex+1], vi_ChrCache, 1)
				}
			}

			vs_Output = strings.ReplaceAll(vs_Output, "\r", "") //<
			vs_Output = strings.ReplaceAll(vs_Output, "\n", "") //>

			sl_OutputNew := strings.Split(vs_Output, " ")
			for index, value := range sl_OutputNew {
				sl_OutputNew[index] = strings.ReplaceAll(value, "\t", " ") //*
			}

			return sl_OutputNew, nil
		}

	} else {
		return nil, nil
	}
}

func (input Console) toSliceEMIF() ([]interface{}, error) {

	ty_Scanner := bufio.NewScanner(os.Stdin)
	//" 1 " 2 3 "4 " " 5" " 六六 " " 七 七 " "八 " " 九" "" " "
	//ty_Scanner := bufio.NewScanner(strings.NewReader("\" 1 \" 2 3 \"4 \" \" 5\" \" 六六 \" \" 七 七 \" \"八 \" \" 九\" \"\" \" \"")) //性能測試用 2019/11/25 14:34:50 耗費:1033.0591 ms
	//1 2 " 3 " "4 " " 5" " 六六 " " 七 七 " "八 " " 九" "" " "
	//ty_Scanner := bufio.NewScanner(strings.NewReader("1 2 \" 3 \" \"4 \" \" 5\" \" 六六 \" \" 七 七 \" \"八 \" \" 九\" \"\" \" \""))
	if ty_Scanner.Scan() {
		vs_Output := ty_Scanner.Text()

		if strings.Contains(vs_Output, "\r") || strings.Contains(vs_Output, "\n") || strings.Contains(vs_Output, "\t") {
			return nil, errors.New("Can't contain ontains : \r \n \t")
		} else if strings.Count(vs_Output, "\"")%2 != 0 {
			return nil, errors.New("Must be double-quote characters ( \" )")
		} else {

			vs_Output = strings.TrimSpace(vs_Output)
			var vi_QutaCount uint64
			for _, value := range []rune(vs_Output) {
				if string(value) == "\"" {
					vi_QutaCount++
					if vi_QutaCount%2 == 1 {
						vs_Output = strings.Replace(vs_Output, "\"", "\r", 1) //<

					} else {
						vs_Output = strings.Replace(vs_Output, "\"", "\n", 1) //>
					}
				}
			}

			vs_Output = strings.ReplaceAll(vs_Output, " \r>", "") //<>

			sl_Output := strings.Split(vs_Output, "\r") //<
			for _, value := range sl_Output {
				vi_ChrIndex := strings.Index(value, "\n") //>
				if vi_ChrIndex > 0 {
					vi_ChrCache := strings.ReplaceAll(value[:vi_ChrIndex+1], " ", "\t") //*
					vs_Output = strings.Replace(vs_Output, value[:vi_ChrIndex+1], vi_ChrCache, 1)
				}
			}

			vs_Output = strings.ReplaceAll(vs_Output, "\r", "") //<
			vs_Output = strings.ReplaceAll(vs_Output, "\n", "") //>

			var sl_OutputNew []interface{}
			for _, value := range strings.Split(vs_Output, " ") {
				sl_OutputNew = append(sl_OutputNew, strings.ReplaceAll(value, "\t", " ")) //*
			}

			return sl_OutputNew, nil
		}

	} else {
		return nil, nil
	}
}

```
