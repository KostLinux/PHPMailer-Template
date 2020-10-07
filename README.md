# PHPMailer for HTML Contact Form

Template was create to setup HTML Contact Form via PHPMailer. (dev env)

Replace smtp with your external E-Mail smtp server, also replace info@domain.com with your mail. PHPMailer will send mail to this address.

$mail->setFrom is address that needs authentication via $mail->Username & $mail->Password
$mail->addAddress is receiver, who will get email from authenticated e-mail.

- $mail->setFrom('info@domain.com', 'INFO');
- $mail->addAddress('testingmail5867@gmail.com', 'test');
