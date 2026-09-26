

  <!-- Font Awesome -->
  <link rel="stylesheet"
        href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">

  <style>
    .button-container {
      display: flex;
      gap: 12px;
      align-items: center;
    }

    .contact-btn {
      display: inline-flex;
      align-items: center;
      gap: 10px;
      padding: 12px 20px;
      border: none;
      border-radius: 8px;
      color: #fff;
      font-size: 16px;
      font-weight: 600;
      text-decoration: none;
      cursor: pointer;
      transition: 0.3s ease;
    }

    .contact-btn i {
      font-size: 20px;
    }

    /* Gmail */
    .gmail-btn {
      background: #ea4335;
    }

    .gmail-btn:hover {
      background: #c5221f;
      transform: translateY(-2px);
    }

    /* WhatsApp */
    .whatsapp-btn {
      background: #25d366;
    }

    .whatsapp-btn:hover {
      background: #1da851;
      transform: translateY(-2px);
    }
  </style>




  <div class="button-container">

    <a href="mailto:example@gmail.com" class="contact-btn gmail-btn">
      <i class="fa-solid fa-envelope"></i>
      Gmail
    </a>

    <a href="https://wa.me/919876543210" class="contact-btn whatsapp-btn" target="_blank">
      <i class="fa-brands fa-whatsapp"></i>
      WhatsApp
    </a>

  </div>

