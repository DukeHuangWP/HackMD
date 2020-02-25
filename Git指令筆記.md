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

  hr,
  code{
    background-color: #999900 !important;
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
  .header,
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


  .navbar .btn-group label.active,
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



###### tags: `Plus` `Git` `GitHub`

# Git指令筆記

## Git設定指令:
>| 命令 |  說明 |
>| --- | --- | --- |
>| git config user.name "Git1"| 設定個別識別資料簽名為 ==`` Git1 ``== | |
>| git config user.email "git@g.com"| 設定個別識別資料E-Mail為 ==`` git@g.com ``== | |
>| git config --global user.name "Git1"| 設定預設識別資料簽名為 ==`` Git1 ``== | |
>| git config --global user.email "git@g.com"| 設定預設識別資料E-Mail為 ==`` git@g.com ``== | |
>
## Git工作目錄:
>| 命令 |  說明 |
>| --- | --- | --- |
>| git init | 初始化當前工作目錄(為該目錄設置Git) | |
>| git add . | 將工作目內所有檔案置入暫存區(stage) | |
>| git add "filename" | 將 ==`` filename ``== 置入暫存區(stage) | |
>| git rm --cached "filename" | 將 ==`` filename ``== 從暫存區(stage)中移除 | |
>| git commit -a | 已變更的檔案提交至本地庫(local repoistry) | |
>| git commit -m "測試編輯評論" "filename" | 將 ==`` filename ``== 提交至本地庫(local repoistry)，並註記 ==`測試編輯評論`== | |
>| git status | 檢查本地庫(local repoistry)與暫存區(stage)的狀態|

## Git查詢指令:
>| 命令 |  說明 | |
>| --- | --- | --- |
>| git log | 顯示Git版本紀錄 | ==`q`==|
>| git log --pretty=oneline | 顯示Git版本紀錄(簡化顯示:無上傳者、時間) | |
>| git log --oneline | 顯示Git版本紀錄(簡化顯示:sh1) | |
>| git reflog | 顯示Git版控操作紀錄 | |
>| git diff | 比較目前檔案與最新版的差異 | |
>| git diff HEAD^ "filename" | 比較檔案 ==`filename`== 與上一版的差異 | |


## Git版控指令:
>| 命令 |  說明 | |
>| --- | --- | --- |
>| git reset --hard "sh1" | Git還原至 ==`sh1`== 版本 | |
>| git reset --hard HEAD^ | Git還原至前一版本 | |
>| git reset --hard HEAD^^^ | Git還原至前三版本 | |
>| git reset --hard HEAD~3 | Git還原至前三版本 | |
>| git checkout "sh1" "filename" | 將檔案 ==`filename`== 還原至指定版本 | |

## Git分支指令:
>| 命令 |  說明 | |
>| --- | --- | --- |
>| git branch -v  | 查詢本地庫的分支 |
>| git branch -a  | 查詢本地庫與遠端庫的分支 |
>| git branch "vername" | 創建新分支並命名為 ==`vername`== |
>| git branch -d "vername" | 刪除分支名稱 ==`vername`== |
>| git branch -D "vername" | 創建新分支並命名為 ==`vername`== |
>| git branch -m "vername" "newname" | 創建新分支 ==`vername`== 更名為 ==`newname`== |
>| git checkout "vername" | 切換分支名稱 ==`vername`== |
>| git checkout -b "vername" | 新增並切換分支名稱 ==`vername`== |
>| git merge "vername" | 將目前版本與分支 ==`vername`== 合併 |
>| git rebase "vername" | 以 ==`vername`== 為基底衍合當前分支 |
>| git checkout --ours "filename" | 切換檔案 ==`filename`== 使用切換前版本分支 |
>| git checkout --theirs "filename" | 切換檔案 ==`filename`== 使用切換後版本分支 |
 

## Git遠端指令:
> | 命令˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰|  說明 |
> | --- | --- | --- |
> | git clone "URL"| 將該遠端儲存庫 ==`URL`== 下載到當前工作目錄 | |
> | git remote| 顯示所有遠端儲存庫版本 | |
> | git remote -v| 顯示所有遠端儲存庫版本與URL | |
> | git remote add "remote_name" "URL" | 將該遠端儲存庫 ==`URL`== 命名為 ==`remote_name`== | |
> | git remote rename "remote_name" "newname" | 將該遠端儲存庫名稱 ==`remote_name`== 更名為 ==`newname`==  | |
> | git remote rm "remote_name" | 移除遠端儲存庫名稱 ==`remote_name`== 與該URL | 
> | git push "remote_name" "vername" | 將分支名稱 ==`vername`== 上傳至遠端儲存庫 ==`remote_name`== | |
> | git pull "remote_name" "vername" | 將遠端儲存庫 ==`remote_name`== 合併至分支名稱 ==`vername`== | |
> | git fetch | 擷取所有遠端儲存庫 | 
> | git fetch <branch_name> | 擷取遠端儲存庫的 ==`varname`== 分支 | 

## Git標籤指令:
> | 命令˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰˰|  說明 |
> | --- | --- | --- |
> | git tag "輕量標籤"| 為目前的版本添加 ==`輕量標籤`== 作為標籤 | |
> | git tag -am "標籤名稱" "註解xxx"| 為目前的版本添加 ==`標籤名稱`== 並以 ==`註解xxx`== 作為註解 | |
> | git tag -d "輕量標籤"| 為目前的版本刪除名稱為 ==`輕量標籤`== 的標籤 | |

---
-
## 上傳至遠端儲存庫失敗(error: failed to push some refs to):
 
 上傳至遠端儲存庫失敗訊息: ==`error: failed to push some refs to`==
 
 最常見的原因為遠端庫資料與本地庫資料有所差異，必須先將遠端庫更新到本地庫中(pull)，==`git pull`== 指令會更新本地庫資料至最新，過程會自動判斷是否有衝突(conflict)，若有須另外藉由 ==`git merge`== 解決問題，若本地庫更新完成後，即可再次 ==`git push`==。
 
 以下是未有衝突發生的成功案例:
 
> ```sass
> d:\Personal File\Desktop\GOLang\GitStudy (master -> origin) 
> λ git commit -a -m "測試衝突"
> [master f8c17be] 測試衝突
>  1 file changed, 2 insertions(+), 1 deletion(-)
> 
> d:\Personal File\Desktop\GOLang\GitStudy (master -> origin) 
> λ git push "初始版" "master"
> To https://github.com/DukeHuang/GitStudy.git
>  ! [rejected]        master -> master (fetch first)
> error: failed to push some refs to 'https://github.com/DukeHuang/GitStudy.git'
> hint: Updates were rejected because the remote contains work that you do
> hint: not have locally. This is usually caused by another repository pushing
> hint: to the same ref. You may want to first integrate the remote changes
> hint: (e.g., 'git pull ...') before pushing again.
> hint: See the 'Note about fast-forwards' in 'git push --help' for details.
> 
> d:\Personal File\Desktop\GOLang\GitStudy (master -> origin) 
> λ git pull "初始版" "master"
> remote: Enumerating objects: 5, done.
> remote: Counting objects: 100% (5/5), done.
> remote: Compressing objects: 100% (2/2), done.
> remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
> Unpacking objects: 100% (3/3), done.
> From https://github.com/DukeHuang/GitStudy
>  * branch            master     -> FETCH_HEAD
>    ccdd6b7..87f9ee8  master     -> 初始版/master
> Merge made by the 'recursive' strategy.
>  A.txt | 3 ++-
>  1 file changed, 2 insertions(+), 1 deletion(-)
> 
> nothing to commit, working tree clean
> 
> d:\Personal File\Desktop\GOLang\GitStudy (master -> origin) 
> λ git push "初始版" "master"
> Enumerating objects: 9, done.
> Counting objects: 100% (8/8), done.
> Delta compression using up to 4 threads
> Compressing objects: 100% (4/4), done.
> Writing objects: 100% (5/5), 664 bytes | 664.00 KiB/s, done.
> Total 5 (delta 0), reused 0 (delta 0)
> To https://github.com/DukeHuang/GitStudy.git
>    87f9ee8..ea840d5  master -> master
> 
> ```
 
 以下是衝突發生並利用 ==`git checkout --ours`== 解決案例: 
> ```sass
> d:\Personal File\Desktop\GOLang\GitStudy (master -> origin) 
> λ git commit -a -m "合併衝突"
> [master da68b1b] 合併衝突
>  2 files changed, 3 insertions(+), 3 deletions(-)
> 
> d:\Personal File\Desktop\GOLang\GitStudy (master -> origin) 
> λ git push "初始版" "master"
> To https://github.com/DukeHuang/GitStudy.git
>  ! [rejected]        master -> master (fetch first)
> error: failed to push some refs to 'https://github.com/DukeHuang/GitStudy.git'
> hint: Updates were rejected because the remote contains work that you do
> hint: not have locally. This is usually caused by another repository pushing
> hint: to the same ref. You may want to first integrate the remote changes
> hint: (e.g., 'git pull ...') before pushing again.
> hint: See the 'Note about fast-forwards' in 'git push --help' for details.
> 
> d:\Personal File\Desktop\GOLang\GitStudy (master -> origin) 
> λ git pull "初始版" "master"
> remote: Enumerating objects: 5, done.
> remote: Counting objects: 100% (5/5), done.
> remote: Compressing objects: 100% (2/2), done.
> remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
> Unpacking objects: 100% (3/3), done.
> From https://github.com/DukeHuang/GitStudy
>  * branch            master     -> FETCH_HEAD
>    ea840d5..27c107b  master     -> 初始版/master
> Auto-merging A.txt
> CONFLICT (content): Merge conflict in A.txt
> Automatic merge failed; fix conflicts and then commit the result.
> 
> d:\Personal File\Desktop\GOLang\GitStudy (master -> origin) 
> λ git checkout --ours "A.txt"
> Updated 1 path from the index
> 
> d:\Personal File\Desktop\GOLang\GitStudy (master -> origin) 
> λ git commit -a -m "解決衝突"
> [master a5b653b] 解決衝突
> 
> d:\Personal File\Desktop\GOLang\GitStudy (master -> origin) 
> λ git push "初始版" "master"
> Enumerating objects: 11, done.
> Counting objects: 100% (10/10), done.
> Delta compression using up to 4 threads
> Compressing objects: 100% (3/3), done.
> Writing objects: 100% (5/5), 489 bytes | 489.00 KiB/s, done.
> Total 5 (delta 1), reused 0 (delta 0)
> remote: Resolving deltas: 100% (1/1), done.
> To https://github.com/DukeHuang/GitStudy.git
>    27c107b..a5b653b  master -> master
> ```

## 解決合併衝突(merge & conflict):
 
將遠端庫更新到本地庫中(pull)，==`git pull`== 指令會更新本地庫資料，合併時易容易發生衝突(conflict)，若使用手動處理衝突可利用編輯器的比較工具分析，修改完成後再使用 ==`git add`== 指令將檔案新增至暫存庫，再 ==`git commit`== 成為一個新版本。


以下是手動處理合併衝突(conflict)的過程:
 
>  ```sass
> d:\Personal File\Desktop\GOLang\GitStudy (master -> origin) 
> λ git pull "初始版" "master"
> remote: Enumerating objects: 9, done.
> remote: Counting objects: 100% (9/9), done.
> remote: Compressing objects: 100% (4/4), done.
> remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
> Unpacking objects: 100% (6/6), done.
> From https://github.com/DukeHuang/GitStudy
>  * branch            master     -> FETCH_HEAD
>    b837896..7a868fc  master     -> 初始版/master
> Auto-merging B.txt
> CONFLICT (content): Merge conflict in B.txt
> Auto-merging A.txt
> CONFLICT (content): Merge conflict in A.txt
> Automatic merge failed; fix conflicts and then commit the result.
> 
> d:\Personal File\Desktop\GOLang\GitStudy (master -> origin) 
> λ git status
> On branch master
> Your branch is ahead of 'origin/master' by 11 commits.
>   (use "git push" to publish your local commits)
> 
> You have unmerged paths.
>   (fix conflicts and run "git commit")
>   (use "git merge --abort" to abort the merge)
> 
> Unmerged paths:
>   (use "git add <file>..." to mark resolution)
> 
>         both modified:   A.txt
>         both modified:   B.txt
> 
> no changes added to commit (use "git add" and/or "git commit -a")
> 
> d:\Personal File\Desktop\GOLang\GitStudy (master -> origin) 
> λ git add .
> 
> d:\Personal File\Desktop\GOLang\GitStudy (master -> origin) 
> λ git commit -a -m "解決合併衝突"
> [master 08d01de] 解決合併衝突
> 
> d:\Personal File\Desktop\GOLang\GitStudy (master -> origin) 
> λ git push "初始版" "master"
> Enumerating objects: 13, done.
> Counting objects: 100% (13/13), done.
> Delta compression using up to 4 threads
> Compressing objects: 100% (4/4), done.
> Writing objects: 100% (7/7), 721 bytes | 721.00 KiB/s, done.
> Total 7 (delta 0), reused 0 (delta 0)
> To https://github.com/DukeHuang/GitStudy.git
>    7a868fc..08d01de  master -> master
>    
> ```

若想還原pull所造成的衝突，可利用 ==`git reset --hard HEAD@{0}`== 指令還原操作:
> ```sass
> d:\Personal File\Desktop\GOLang\GitStudy (master -> origin) 
> λ git pull "初始版" "master"
> remote: Enumerating objects: 9, done.
> remote: Counting objects: 100% (9/9), done.
> remote: Compressing objects: 100% (4/4), done.
> remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
> Unpacking objects: 100% (6/6), done.
> From https://github.com/DukeHuang/GitStudy
>  * branch            master     -> FETCH_HEAD
>    b837896..7a868fc  master     -> 初始版/master
> Auto-merging B.txt
> CONFLICT (content): Merge conflict in B.txt
> Auto-merging A.txt
> CONFLICT (content): Merge conflict in A.txt
> Automatic merge failed; fix conflicts and then commit the result.
> 
> d:\Personal File\Desktop\GOLang\GitStudy (master -> origin) 
> λ git status
> On branch master
> Your branch is ahead of 'origin/master' by 11 commits.
>   (use "git push" to publish your local commits)
> 
> You have unmerged paths.
>   (fix conflicts and run "git commit")
>   (use "git merge --abort" to abort the merge)
> 
> Unmerged paths:
>   (use "git add <file>..." to mark resolution)
> 
>         both modified:   A.txt
>         both modified:   B.txt
> 
> no changes added to commit (use "git add" and/or "git commit -a")
> 
> d:\Personal File\Desktop\GOLang\GitStudy (XTest -> origin) 
> λ git reflog
> d70266d (HEAD -> XTest) HEAD@{0}: commit: Xtest Ver
> b837896 HEAD@{1}: checkout: moving from master to XTest
> 08d01de (初始版/master, master) HEAD@{2}: commit (merge): 解決合併衝突
> d7dfe6c HEAD@{3}: commit: X修改版
> b837896 HEAD@{4}: commit: 合併版本
> a5b653b HEAD@{5}: commit (merge): 解決衝突
> da68b1b HEAD@{6}: commit: 合併衝突2
> ea840d5 HEAD@{7}: pull 初始版 master: Merge made by the 'recursive' strategy.
> f8c17be HEAD@{8}: commit: 測試衝突
> ccdd6b7 HEAD@{9}: commit: 修改初始注解
> 948d58b HEAD@{10}: commit: 修改初始注解
> e183b37 HEAD@{11}: commit: 初始版
> 0c14f3d (origin/master, origin/HEAD) HEAD@{12}: clone: from https://github.com/DukeHuang/GitStudy.git
> 
> d:\Personal File\Desktop\GOLang\GitStudy (XTest -> origin) 
> λ git reset --hard HEAD@{0}
> HEAD is now at d70266d Xtest Ver
> ```