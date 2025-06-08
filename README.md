# my-css-files
<style>
  .question-block {
       font-family: 'Baloo Da 2', Arial, sans-serif;
       font-size: medium;
       background: #fff;
       border: 1px solid #ccc;
       border-radius: 10px;
       padding: 15px;
       margin-bottom: 20px;
       box-shadow: 0 2px 6px rgba(0,0,0,0.1);
       display: none;
        }
       .options {
        margin: 10px 0;
        }
       .options span {
        display: block;
        padding: 5px 10px;
         }

     .acc {
       background-color: #28a745;
       color: white;
       padding: 10px 20px;
       font-size: 16px;
       border: none;
       border-radius: 50px;
       cursor: pointer;
       transition: background-color 0.3s ease, transform 0.3s ease;
       box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
       margin-top: 10px;
     }

     .acc:hover, .active {
       background-color: #218838;
       transform: scale(1.05);
     }

     .pnl {
       display: none;
       margin-top: 15px;
       padding: 12px;
       background-color: #eaf7e4;
       border-radius: 10px;
       color: #3e8e41;
       font-size: 16px;
       border: 2px solid #28a745;
     }

     .pagination {
       text-align: right;
       margin-top: 20px;
     }

     .pagination button {
       background-color: #007bff;
       color: white;
       border: none;
       padding: 8px 12px;
       margin: 2px;
       border-radius: 5px;
       cursor: pointer;
     }

     .pagination button.active {
       background-color: #0056b3;
     }
</style>
