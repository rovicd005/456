using System;
using System.Windows.Forms;

namespace YourNamespace
{
    public partial class YourForm : Form
    {
        private PictureBox pictureBox1;
        private PictureBox pictureBox2;

        public YourForm()
        {
            InitializeComponent();
            InitializePictureBoxes();
        }

        private void InitializePictureBoxes()
        {
            pictureBox1 = new PictureBox();
            pictureBox1.Click += PictureBox1_Click;

            pictureBox2 = new PictureBox();
            pictureBox2.Click += PictureBox2_Click;
        }

        private void PictureBox1_Click(object sender, EventArgs e)
        {
            // Your code logic for pictureBox1_Click
        }

        private void PictureBox2_Click(object sender, EventArgs e)
        {
            // Your code logic for pictureBox2_Click
        }
    }
}
