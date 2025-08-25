body {
  font-family: Arial, sans-serif;
  background: #f5f5f5;
  padding: 2px;
  margin: 0;
}

.container {
  width: 100%;
  padding: 8px;
  box-sizing: border-box;
}

.test-box {
  background: #fff;
  border: 1px solid #ccc;
  border-radius: 8px;
  padding: 8px 12px;
  display: none;
  justify-content: space-between;
  align-items: center;
  width: 100%;
  margin: auto;
  margin-bottom: 16px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.08);
  box-sizing: border-box;
}

.test-info {
  max-width: 100%;
}

.test-no {
  background: #000;
  color: #fff;
  font-size: 12px;
  font-weight: 800;
  display: inline-block;
  padding: 1px 6px;
  border-radius: 5px;
  width: fit-content;
  margin-bottom: 5px;
}

.title {
  color: red;
  font-size: 17px;
  font-weight: bold;
  margin-bottom: 2px;
}

.details {
  font-size: 12px;
  font-weight: bold;
  color: #444;
}

.date {
  color: green;
  font-weight: bold;
  font-size: 12px;
}

.start-btn {
  display: inline-block;
  background-color: white;
  color: black;
  border: 1px solid #333;
  padding: 2px 10px;
  border-radius: 16px;
  font-weight: 800;
  font-size: 13px;
  text-decoration: none;
  white-space: nowrap;
  transition: 0.3s;
  -webkit-tap-highlight-color: transparent;
  outline: none;
}

.start-btn:focus {
  outline: none;
  box-shadow: none;
}

.start-btn:hover {
  background-color: #009999;
  color: white;
  border: none;
}

#loadMoreBtn {
  display: block;
  margin: 10px auto;
  padding: 8px 15px;
  background: #007bff;
  color: #fff;
  font-size: 16px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

@media screen and (max-width: 480px) {
  .title {
    font-size: 14px;
  }

  .details {
    font-size: 12px;
  }

  .start-btn {
    padding: 3px 8px;
    font-size: 11px;
  }
}
